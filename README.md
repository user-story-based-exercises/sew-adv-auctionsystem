SEW | CORE | Auctionsystem

## User Story 1
*As an auctioneer, I want to have an automated auctioning system, so that I can reduce my workload.*

### Acceptance Criteria
- A function sell(<name of object>) is available.
- The function counts from one to two and then sells the object.
- The console messages look like the following: 
  - <name of object> going once...
  - <name of object> going twice...
  - <name of object> sold!  
- The first message appears immideatly after invoking the function.
- The other messages appear with a delay of one second each.
- There can be multiple auctions at the same time.

## User Story 2
*As an auctioneer, I want to have only a single auction running at the same time, so that I can reduce my stress.*

### Acceptance Criteria
- An class named Auctioneer is available.
- There is only a single method within this class, being the function sell(<name of object>).
- Once an auction is running, no other auctions are allowed, meaning further calls of sell will be ignored.

