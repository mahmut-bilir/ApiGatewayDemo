This project includes an API Gateway built using .NET 8 and two microservices (Products API and Orders API). The API Gateway is configured using Ocelot and handles routing operations.

Projects
ApiGateway
The API Gateway is an API gateway configured using Ocelot. It routes requests to microservices.

Port: http://localhost:5000
Configuration File: ocelot.json
ProductsApi
The Products API is a microservice that provides data about products.

Port: http://localhost:5001
Endpoint: /api/products
Sample Response:
{
"Message": "Products API is working"
}
