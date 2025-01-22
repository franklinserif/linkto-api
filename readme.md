## Link Shortener API

This is a RESTful API built with Node.js and TypeScript to create and manage shortened links. The application is dockerized and uses PostgreSQL as the database. It includes user authentication and a dashboard to monitor link statistics.

### Features

- Create shortened links with expiration dates.

- Manage user authentication with JWT (Access Token and Refresh Token).

- Validate the status of links (active or expired).

- Track link visits.

- Dashboard to view links, statistics, and visits.

- Uses Docker for easy deployment.

### Technologies Used

- Backend: Node.js, TypeScript, NestJS

- Database: PostgreSQL with TypeORM

- Authentication: Passport.js with JWT

- Testing: Jest

- Containerization: Docker, Docker Compose

- Documentation: Swagger
