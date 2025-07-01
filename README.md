 # Steps

 Follow this 7-step process to do well in a System Design Round

1 - Requirements Clarification
In the first step, clarify functional and non-functional requirements. Ask questions to understand the core features of the system as well as non-functional aspects such as data volume, availability, scale, etc.

2 - Capacity Estimation
Next, estimate the capacity of the system. Focus on attributes like the number of users, traffic, storage/memory needs, and compute and networking requirements.

3 - Create High-Level Design
Break down the system into components such as client apps, servers, load balancers, databases, etc. 

Start with drawing a simple block diagram that shows these components and their potential interaction with each other. Focus on the data flow.

4 - Database Design
Model the data and choose the right database type for the system. Once done, focus on the database schema.

5 - Interface Design
Next, focus on the interfaces to the system. This could be API endpoints or event models exchanged between the various components of the system. Also, choose a communication approach such as REST, GraphQL, gRPC, or an event-driven

6 - Scalability and Performance
Address the scalability, performance, and latency aspects of the system by suggesting techniques that will be used. For example, vertical and horizontal scaling, caching, indexing, denormalizing, sharding, replication, CDNs, etc.

7 - Reliability and Resiliency
Lastly, address the reliability and resiliency of the design. Identify single points of failure and mitigate their impact.


 # Rules
 
 - Read-heavy systems? Use a Cache
 - Low-latency needs? Combine Cache & CDN
 - Write-heavy systems? Implement a Message Queue for async processing
 - ACID compliance? Choose RDBMS/SQL
 - Unstructured data? Go for NoSQL
 - Handling large files (videos, images)? Use Blob/Object Storage
 - Complex pre-computation (e.g., news feed)? Combine Message Queue & Cache
 - High-volume search? Implement Elasticsearch, Tries, or Search Indexing
 - Scaling SQL databases? Consider Sharding
 - High availability & performance? Use a Load Balancer
 - Global data delivery? Leverage a CDN
 - Graph-based relationships? Choose a Graph Database
 - Scaling components? Implement Horizontal Scaling
 - High-performance queries? Optimize with Database Indexes
 - Bulk processing? Use Batch Processing & Message Queues
 - Preventing DDoS attacks? Apply a Rate Limiter
 - Microservices? Use an API Gateway
 - Single point of failure? Implement Redundancy
 - Fault tolerance? Ensure Data Replication
 - Real-time communication? Use WebSockets
 - Distributed failure detection? Implement Heartbeat
 - Ensuring data integrity? Apply Checksum Algorithm
 - Decentralized data transfer? Use Gossip Protocol
 - Efficient server scaling? Implement Consistent Hashing
 - Location-based features? Use Geohash or Quadtree
 - High availability vs consistency? Eventual Consistency is key
 - Handling large network requests? Implement Pagination
 - Cache eviction? Use LRU (Least Recently Used)
 - Handling traffic spikes? Implement Autoscaling
 - Analytics & audit trails? Store in Data Lakes
 - Large-scale connections? Optimize with Connection Pooling & Protobuf
 - Preventing system overload? Use Token Bucket & Leaky Bucket algorithms
 - Zero-downtime deployments? Apply Blue-Green Deployment


 https://github.com/RobertoFreireFerrazPassos/Interview-Full-Stack/tree/main/systemdesign