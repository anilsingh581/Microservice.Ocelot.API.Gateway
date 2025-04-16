## Building Microservices using ASP.Net Core

# Microservice architecture with Ocelot API Gateway in ASP.Net Core

# Topics Covered
- Microservices Architecture Overview
- Monolith vs Microservices
- Configure Microservices with Ocelot API Gateway 
- Run and test individual microservice with swagger.

If you want more about this, Do check out my Article 👇🏻

[**Code-Sample**](https://www.code-sample.com/ "Code-Sample")

# Real-world Enhancements
- Add Polly for retry, circuit breaker.
- Use Swagger with API Gateway using tools like SwaggerForOcelot.
- Integrate logging/tracing (e.g., Serilog + OpenTelemetry).
- Add Docker/Kubernetes deployment.

# Project Structure
# Example structure:

/ApiGateway           → Ocelot API Gateway
/CustomerService      → Microservice 1
/OrderService         → Microservice 2
/ProductService       → Microservice 3
Each service runs independently, communicates via REST (or gRPC/event-based in advanced cases).

