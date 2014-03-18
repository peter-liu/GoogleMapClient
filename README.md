GoogleMapClient
===============

java implementation of google map api

Show Case
===============
// 1.Create Request
GMatrixRequest req = GRequestFactory.createMatrixReq();

// 2.Add Origins
req.addOrigin("beijing");
req.addOrigin("nanjing"); 
req.addOrigin("shanghai");
req.addOrigin("xingjiang"); 
req.addOrigin("chongqing");

// 3.Add Destinations
req.addDestination("chengdu");

// 4.Execute
GResponse response = GoogleMapClient.execute(req);
