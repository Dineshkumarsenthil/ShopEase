# ShopEase - Microservices-Based E-Commerce Management System

**Prepared by:** Dineshkumar S
**Stage:** Day 1 - Study, documentation and architecture design (no code yet)

ShopEase is an e-commerce system built with microservices. It has an API Gateway and five services (Authentication, User, Product, Order and Payment). Each service has its own MySQL database and the services talk to each other using REST APIs. Day 1 covers only the study and design work.

## Folder contents

- `docs/01_monolithic_vs_microservices.docx` - comparison of monolithic and microservices architecture
- `docs/02_service_responsibilities.docx` - what each service does and does not do
- `docs/03_database_ownership.docx` - database per service and why services must not share databases
- `docs/04_rest_api_and_http_notes.docx` - HTTP methods, status codes, JSON examples and endpoints
- `docs/05_service_communication_workflow.docx` - order flow and error handling
- `diagrams/shopease_architecture.png` - complete architecture diagram
- `diagrams/database_ownership.png` - database ownership diagram
- `diagrams/service_communication_flow.png` - sequence diagram of the order flow
- `progress/day1_progress_update.md` - daily progress update
- `submission/ShopEase_Day1_Dineshkumar_S.pdf` - all documents combined in one PDF
