## CloudChef - Software Architecture Design

CloudChef is a cloud-based meal delivery platform designed to connect diners with local and national restaurants and chefs. This repository outlines the architectural framework and decision-making process behind the platform, emphasizing scalability, resilience, and cost-effectiveness.

### Key Features
- Curated selection of diverse cuisines.
- User-friendly ordering interface with real-time delivery tracking.
- Flexible delivery options.
- Integration with Stripe for payments and Google Maps for delivery tracking.

### Architectural Decisions
- **Database:** MongoDB for scalability and flexibility.
- **Architecture:** Microservices for agility and independent deployment.
- **Cloud Provider:** AWS for comprehensive services and security.
- **API Gateway:** Amazon API Gateway for secure and managed API access.
- **Authentication:** OAuth 2.0 and JWT for secure and user-friendly authentication.

### Architecture Models
- **C4 Model:** Context, Container, and Component views detailing the system architecture.
- **Key Components:** React Native and React.js for the user interface, Node.js and Spring Boot for microservices, and MongoDB for data storage.

### Key Qualities
- **Cost-effective:** Utilizing AWS's pay-as-you-go model and MongoDB.
- **Resilient:** Microservices architecture and distributed MongoDB for fault tolerance.
