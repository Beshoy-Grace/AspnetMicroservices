# AspnetMicroservices

There is a couple of microservices which implemented e-commerce modules over Catalog, Basket, Discount and 
Ordering microservices with NoSQL (MongoDB, Redis) and Relational databases (PostgreSQL, Sql Server)
with communicating over RabbitMQ Event Driven Communication and using Ocelot API Gateway.

docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d

Wait for docker compose all microservices. That’s it! (some microservices need extra time to work so please wait if not worked in first shut)

You can launch microservices as below urls:

Catalog API -> http://host.docker.internal:8000/swagger/index.html

Basket API -> http://host.docker.internal:8001/swagger/index.html

Discount API -> http://host.docker.internal:8002/swagger/index.html

Ordering API -> http://host.docker.internal:8004/swagger/index.html

Shopping.Aggregator -> http://host.docker.internal:8005/swagger/index.html

API Gateway -> http://host.docker.internal:8010/Catalog

Rabbit Management Dashboard -> http://host.docker.internal:15672 -- guest/guest

Portainer -> http://host.docker.internal:9000 -- admin/admin1234

pgAdmin PostgreSQL -> http://host.docker.internal:5050

Elasticsearch -> http://host.docker.internal:9200 -- To Be Develop

Kibana -> http://host.docker.internal:5601 -- To Be Develop

Web Status -> http://host.docker.internal:8007 -- To Be Develop

Web UI -> http://host.docker.internal:8006
