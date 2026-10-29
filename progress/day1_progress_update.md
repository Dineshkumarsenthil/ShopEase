# Day 1 Progress Update - ShopEase

**Name:** Dineshkumar S

## Tasks completed
- Studied monolithic and microservices architecture.
- Documented the responsibilities of the six services.
- Studied database ownership (database per service).
- Prepared notes on REST APIs, HTTP methods and status codes.
- Prepared the service-to-service communication workflow.
- Prepared the architecture, database ownership and sequence diagrams.

## Topics learned
- Differences between monolithic and microservices architecture.
- Why each microservice needs its own database.
- GET, POST, PUT, PATCH, DELETE and common status codes (200, 201, 400, 401, 404, 422, 503).
- How the Order Service calls the Product and Payment services.
- Error handling with timeouts, retries and undoing earlier steps.

## Documents or diagrams prepared
- 5 Word documents (comparison, responsibilities, database ownership, REST notes, communication workflow).
- 3 diagrams (architecture, database ownership, order flow).

## Issues faced and solutions identified
- Issue: I was not sure why the Order Service should call the Product Service API instead of reading product_db directly to check stock.
- Solution: I learned that direct database access creates tight coupling, because if the Product team changes a table, the Order Service breaks. It also skips the Product Service's business rules. So the Order Service calls GET /products/{id} and the Product Service returns the data.

## Pending work
- Review all documents once more and practise explaining them.
- Start implementation only after the Day 1 review is done.
