# ApiGatewayDemo

Bu proje, .NET 8 kullanılarak oluşturulmuş bir API Gateway ve iki mikro hizmet (Products API ve Orders API) içerir. API Gateway, Ocelot kullanılarak yapılandırılmıştır ve yönlendirme işlemlerini yönetir.

## Projeler

### ApiGateway

API Gateway, Ocelot kullanılarak yapılandırılmış bir API geçiş kapısıdır. Mikro hizmetlere yapılan istekleri yönlendirir.

- **Port:** `http://localhost:5000`
- **Yapılandırma Dosyası:** `ocelot.json`

### ProductsApi

Products API, ürünlerle ilgili verileri sunan bir mikro hizmettir.

- **Port:** `http://localhost:5001`
- **Endpoint:** `/api/products`
- **Örnek Yanıt:**
  ```json
  {
    "Message": "Products API is working"
  }
