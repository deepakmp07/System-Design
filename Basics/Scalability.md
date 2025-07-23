# Scalability
 - Scalability is the property of the System to handle a growing amount of Load by adding resources to the System

## How System Grows?
 - more Users
 - more feature
 - more complexity
 - more Geographies
 - more Data

## How to handle this Growth?
 - Vertical Scaling
   - Adding power to your machines(CPU, RAM, storage)
 - Horizontal Scaling
   - Adding more machines
 - Load Balancing
   - Distributing traffic across multiple servers, so no single server is overwhelmed.
 - Caching
   - Storing frequently accessed data in-memory to reduce load on server or db.
   - Implementing caching can dramatically improve response times.
 - Content Delivery Network
   - Storing static assets like images, video, which can distribute to nearby users.
   - This can reduce latency and result in faster load times.
 - Sharding / Partition
   - Partitioning means splitting data or functionality across multiple servers to distribute workload
 - Asynchronous communication
    - Asynchronous communication means deferring long-running or non-critical tasks to background queues or message brokers.
    - This ensures your main application remains responsive to users.
 - Microservice Architecture
    - Micro-services architecture breaks down application into smaller, independent services that can be scaled independently.
    - This improves resilience and allows teams to work on specific components in parallel.
 - Auto - Scaling
    - Auto-Scaling means automatically adjusting the number of active servers based on the current load.
    - This ensures that the system can handle spikes in traffic without manual intervention.
 - Multi-region Deployment
    - Deploy the application in multiple data centers or cloud regions to reduce latency and improve redundancy.