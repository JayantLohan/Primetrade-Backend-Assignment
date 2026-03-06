Scalability Note
To handle 10k+ users, I would implement:


Redis Caching: To speed up frequent API requests.


Load Balancing: Using Nginx to distribute traffic across servers.


Microservices: Splitting Auth and CRUD for independent scaling.


Indexing: Optimizing MongoDB fields for faster lookups.


Docker: For consistent deployment and scaling.# Primetrade-Backend-Assignment
