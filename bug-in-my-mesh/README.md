# There's a Bug in My Service Mesh! What Do You Do When the Mesh is At Fault?
### - Ana Calin, Paybase & Risha Mars, Buoyant

A service mesh is an increasingly necessary tool when running and debugging
modern applications. But what do you do when there’s a bug in the mesh itself?

Paybase offers the most flexible, developer-native, API-driven solution for
payments, compliance and risk. They use the Linkerd service mesh to process all
requests that come through their complex system of microservices, where it is
highly useful for out of the box gRPC load balancing which allows Paybase to
scale their application.

In this talk, Ana and Risha will talk about different Linkerd bugs that Paybase
encountered after deploying Linkerd to their staging environment, and how they
worked with the Linkerd maintainers to track them down and squash them.

This talk also explores the relationship between companies that rely on open
source software and their interactions with maintainers in the path to getting
bugs fixed.
