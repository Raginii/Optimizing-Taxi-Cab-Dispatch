To formulate the static DARP with time-varying travel times, hard time windows, single depot and homogeneous vehicles as a Mixed Integer optimization problem. Given the number of requests and its details like pickup and drop locations, pickup time and distance between pickup and drop location, our model tries to service each request and route the available cabs at the depot to each pickup location in such a way that the weighted combination of the number of cabs dispatched and the total distance covered by the fleet is minimum. All the cabs are dispached from the depot and they return back to the depot at the end of the day.

Since each request has a hard time window, it is interesting to note that the model dispatches another cab from the depot if the already dispatched cabs are serving another requests. For a cab which has already served a request and is near to the next requested pickup location, the model routes the same cab to next pickup request instead of dispatching another cab. The model looks at every aspect of the information available and generates an assignment matrix which shows the cab number assigned to each request. The problem is an NP-hard problem which includes scheduling along with routing. It is modelled as a Mixed Integer Program.

In today’s on-demand economy, the taxi dispatch problem is everywhere. It doesn’t matter if you transport people, deliver food from restaurants, or pick up and drop off courier packages; the logistics of managing an on-demand fleet is all the same. All of these involve Route Optimization. Route optimization is about finding the shortest total driving time, given a fleet of vehicles and a host of requests with their constraints. This is also known as the Vehicle Routing Problem (VRP)citations. In our case, we need to solve a same-day Pickup and Delivery Problem with Time-Windows (PDPTW).
