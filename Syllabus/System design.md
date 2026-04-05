Bilkul, yeh raha **System Design ka practical roadmap** jisme **concept + development** dono ek saath hain.  
Pehle **main topics** diye gaye hain – aage inhi ke andar coding/projects aayenge.

---

## 1. Building Blocks of Scalable Systems  
**(Fundamental components jo har system mein hote hain)**

- **Load Balancer** (Round Robin, Least Connections, Hashing)  
- **Caching** (Redis, Memcached, CDN, Browser cache)  
- **Database** (SQL vs NoSQL, Sharding, Replication, Indexing)  
- **Message Queue** (Kafka, RabbitMQ, SQS)  
- **File Storage / CDN** (S3, CloudFront, Blob storage)  
- **API Gateway** (Rate limiting, Authentication, Routing)

---

## 2. Communication Protocols & Data Flow  
- **REST vs gRPC vs GraphQL**  
- **HTTP/2, WebSockets** (real-time apps)  
- **Polling vs Webhooks**  
- **Synchronous vs Asynchronous** processing

---

## 3. Database Design & Scaling  
- **Normalization vs Denormalization**  
- **Read Replicas & Write Master**  
- **Horizontal vs Vertical Sharding**  
- **CAP Theorem** (CP vs AP systems)

---

## 4. Caching Strategies  
- **Cache Aside, Read Through, Write Through, Write Back**  
- **Cache Eviction** (LRU, LFU, TTL)  
- **Cache Invalidation problem**  
- **Distributed Cache** (Redis Cluster)

---

## 5. Message Queues & Event-Driven Architecture  
- **Producer-Consumer**  
- **Dead Letter Queue**  
- **Idempotency**  
- **Event Sourcing** (basic)

---

## 6. Microservices & Monolith  
- **Service Discovery** (Consul, Eureka)  
- **API Composition vs BFF**  
- **Circuit Breaker** (Resilience4J, Hystrix)  
- **Distributed Tracing** (Jaeger, Zipkin)

---

## 7. Real-World Case Studies (Dev ke liye zaroori)  
- **TinyURL** (shortener)  
- **WhatsApp** (real-time chat)  
- **Netflix** (video streaming + recommendation)  
- **Uber** (matching + location tracking)  
- **E-commerce** (inventory + payment)

---

## Agli steps chaahiye toh batao:  
- Har topic ke andar **code/project kya banayenge**  
- **Kis order mein padhna + implement karna hai**  
- **Resources (YouTube + GitHub + blog + practice platform)**
