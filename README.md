# Ocelot API Gateway Project

## Overview

This project demonstrates the use of Ocelot as an API Gateway in a .NET application. Ocelot is a lightweight API Gateway that is used to route requests to various downstream services, manage load balancing, and provide various other API management functionalities.

## Project Structure

- **`ocelot.json`**: Configuration file for Ocelot, defining routing rules and downstream services.
- **`Program.cs`**: Main entry point of the .NET application where Ocelot is configured and used.

## Setup and Configuration

### Prerequisites

- .NET 6.0 or later
- NuGet Package Manager

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/mahmut-bilir/ApiGatewayDemo.git
   cd ApiGatewayDemo

 2. **Test Routes**

Access the configured routes via:

## http://localhost:5000/gateway/products for products
## http://localhost:5000/gateway/orders for orders
