# Air BnB Clone Project

The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. This project enables learners to understand complex architectures, workflows, and collaborative team dynamics while building a scalable web application.


## Project Goals
- Design a scalable backend architecture
- Build secure APIs for property booking
- Model real-world relational database structures
- Apply CI/CD best practices
- Strengthen collaborative development using GitHub


## Team Roles
- Backend Developer - Develop the backend side of the project and intergration with third parties APIs.
- Database Administrator - Designs the database schema, manages relationships between entities, ensures data integrity, and optimizes queries.
- Project manager - Oversees timelines, task distribution, documentation, and ensures alignment with project requirements.
- DevOps Engineer - Sets up CI/CD pipelines, manages containerization using Docker, and ensures smooth deployment and automation.


## Technology Stack
- **Django**: Backend web framework used to build scalable APIs.
- **Django REST Framework (DRF)**: Used for creating RESTful APIs.
- **PostgreSQL / MySQL**: Relational database for storing application data.
- **GraphQL**: Enables flexible and efficient API queries.
- **Docker**: Containerization tool for consistent development and deployment environments.
- **GitHub Actions**: CI/CD tool for automating testing and deployment workflows.



## Database Design
1. Users:
    - id
    - name
    - email
    - password
    - role

2. Properties:
    - id
    - title
    - location
    - price_rates_per_night
    - owner_id

3. Bookings:
    - id
    - user_id
    - property_id
    - start_date
    - end_date

4. Reviews:
    - id
    - user_id
    - preperty_id
    - rating
    - comment

5. Payments:
    - id
    - timestamp
    - amount
    - payment_status
    - booking_id

## Feature Breakdown
### User Management
Handles user registration, authentication, and profile management. Ensures secure access to the platform.

### Property Management
Allows hosts to create, update, and manage property listings including pricing and availability.

### Booking system
Enables users to book available properties, manage reservations, and track booking history.

### Reviews
Allows guests to leave ratings and reviews, improving trust and transparency.

### Payment Processing
Handles booking payments securely and tracks transaction history.


## API Security
- **Authentication**: Uses token-based authentication to verify users.
- **Authorization**: Role-based access control ensures users only access permitted resources.
- **Rate Limiting**: Prevents abuse and protects APIs from excessive requests.
- **Data Validation**: Ensures only valid and safe data is processed.


## CI/CD Pipeline

CI/CD pipelines automate testing, building, and deployment processes, reducing errors and improving development efficiency.

### Tools Used
- **GitHub Actions**: Automates testing and deployment workflows.
- **Docker**: Ensures consistent environments across development and production.

CI/CD enables faster iteration, reliable deployments, and improved collaboration.
