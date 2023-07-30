# Scalable Services

## Modules

1.	Getting to know Scalability: 
    * Introduction to Performance, Consistency and availability
    * What is scalability?
    * Need for scalable architectures
    * Principles of Scalability
    * Guidelines for Building Highly Scalable Systems 
    * Architecturally scalable requirements 
    * Challenges for Scalability
    * YouTube case Study
2.	Popular scaling approaches 
    * Managing & processing high volumes of data 
        *  Partitioning and sharding 
        *  Distributed data (CAP theorem, NoSQL, HDFS)
        *  Distributed Processing (Map reduce, Spark)
    * Managing high velocity data streams (Kafka)
        *  Video streaming: Netflix, YouTube, use of CDN
        *  Real time analytics: Credit card fraud detection
        *  Web conferencing: WebEx, Zoom
        *  Edge computing: IoT systems
    * Managing high volume transactions
        *  Service Replicas & load balancing
        *  Minimizing event processing: Command Query Responsibility Segregation (CQRS)
        *  Asynchronous communication
        *  Caching techniques: Distributed cache, global cache
    * Scalability features in the Cloud (AWS, Azure, Google)
        *  Auto-scaling
        *  Horizontal and vertical scaling
        *  Use of Load balancers
        *  Virtualization
        *  Serverless computing
    * Best Practices for Achieving Scalability
3.	Microservices - Introduction	
    * Challenges with Monolith applications
    * Microservices architecture
    * Advantages and disadvantages of Microservices
    * Process & organization for microservices
4.	Decomposition strategies
    * Decomposition by business capability
    * Decomposition by business domain 
    * Decomposition guidelines
    * Obstacles to decomposing an application into services
    * Defining service APIs
5.	Communication between Microservices
    * Inter-service communication
        *  Synchronous communication (REST, gRPC)
        *  Asynchronous communication
    * Application boundary
        *  API gateway
        *  API design
        *  Creating and versioning APIs
        *  API security
        *  Backends for frontends
6.	Transaction management
    * Distributed transactions
    * Implementation
    * Challenges
    * Solutions
    * Sagas
7.	Building with pipelines
    * Continuous integration
    * Tooling
    * Repository patterns – Multi-repo, mono-repo
8.	Designing reliable microservices 
    * Sources of failure, cascading failures
    * Designing reliable communication: Retires, async. Comm., circuit breakers
    * Maximizing service reliability: Load balancing, Rate limiting (Queues, Throttling)
    * Service mesh
9.	Securing and Testing scalable services
    * Securing code and repositories
    * Using Authentication and Authorization
    * Unit testing
    * Integration testing 
    * Load testing
10.	Deploying Microservices
    * Service startup
    * Running multiple instances
    * Adding load balancer
    * Service to host models
        * Single Service Instance to Host
        * Multiple static Service Per Host
        * Multiple scheduled services per host
    * Deploying services without downtime: Canaries, Blue-Green, & rolling deploys
    * Deploying microservices using Serverless deployment
11.	Deployment with Containers
    * Introduction to containers
    * Containerizing a service
    * Deploying to a cluster
12.	Monitoring
    * Golden signals
    * Types of metrics
    * Recommended practices
    * Collecting metrics
    * Instrumenting
    * Raising sensible & actionable alerts
    * Using logs & traces
    * Useful info in log entries
    * Tools for logging
    * Logging the right information
    * Tracing interaction between services
    * Visualizing traces
13.	Kubernetes
    * Dockers for CaaS
    * What is Kubernetes
    * Deployment of Microservices using Kubernetes
    * Scalability in Kubernetes
    * Security in Kubernetes
    * CI/CD using Kubernetes
    * Kubernetes Dashboard
