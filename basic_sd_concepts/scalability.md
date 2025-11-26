Scalability in System design:
As the number of users or the volume of data grows, system performance can start to degrade. To handle higher demand efficiently, systems must be designed to scale. Below are common strategies used to build scalable systems.

1. Vertical Scaling:
    Vertical scaling means upgrading your existing machine — adding more RAM, CPU, or storage to improve performance.

2. Horizontal scaling:
    Instead of one powerful machine, add more machines (nodes/servers) and distribute the workload.

3. Load balancers:
    A load balancer distributes incoming traffic across multiple servers so no server is overwhelmed.

4. CDN(Content Delivery Network):
    CDN disributes web data(static images) closer to the users. This reduce latency and increase reponse time resulting in faster loads.

5. Auto scaling:
    Auto scaling is a process of adding/removing machines automatically based on the current load demand.

6. Caching:
    Caching is a process of storing frequently accessed data in-memory to avoid DB hits every time. If the data is not availble in the cache, the request will fetch the data from DB.

7. Sharding:
    Sharding is a process of splitting the data into mulitple nodes/server to avoid bottleneck with more data.

8. Asynchornous process:
    Asynchronous is a process of processing the long running request in background instead of foreground.

9. Multiple region deployment:
    This ensures users are served from the nearest location. This reduces latency and increases response time.

10. Micro services architecture:
    Splitting the monolithic app into multiple microservices to scale it independently.
