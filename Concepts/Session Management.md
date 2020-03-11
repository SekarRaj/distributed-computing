Session Management
    Management of user sessions in a distributed system can be done in two ways

Sticky Sessions
    Each user request is routed to the same server by the load balancer
    Identified by a header or client-cookies
    Session is managed by the node that serves the request
    - Node failure could lead to session loss
    - Node overload

Distributed Session Management
    - Using in-memory key-value data store
    - Boosts overall perforamnce
    - With replicate session loss can be prevented

    - Additional infra layer/abstraction
    - Integration plumbing with the cache required
