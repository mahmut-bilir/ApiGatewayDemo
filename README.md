This project includes an API Gateway and two microservices (Products API and Orders API) built using .NET 8. The API Gateway is configured with Ocelot and manages routing operations.

Projects
ApiGateway
The API Gateway is an API gateway configured with Ocelot. It routes requests to the microservices.

Port: http://localhost:5000
Configuration File: ocelot.json
ProductsApi
The Products API is a microservice that provides data related to products.

Port: http://localhost:5001
Endpoint: /api/products
Sample Response:

{
  "Message": "Products API is working"
}
