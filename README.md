CS 470 – Full Stack Web Application in the Cloud
Author

Bradly Grigg

Project Overview

This project demonstrates the development, migration, and deployment of a full stack web application using cloud-based services. The application was originally built using a traditional architecture and then enhanced through the use of AWS cloud technologies to improve scalability, performance, and availability.

The final solution integrates a frontend interface, backend API, and cloud-based data storage, showcasing modern development practices and cloud deployment strategies.

Technologies Used
Frontend
Angular
HTML5 / CSS3
Bootstrap
Backend
Node.js
Express.js
Cloud Services (AWS)
Amazon S3 – Static website hosting
AWS Lambda – Serverless backend functions
Amazon API Gateway – API routing and management
Amazon DynamoDB – NoSQL database
AWS IAM – Role-based access control
Key Features
Full stack web application with frontend and backend integration
RESTful API design using API Gateway and Lambda
Cloud-hosted frontend using Amazon S3
Scalable database solution with DynamoDB
Secure access management using IAM roles and policies
Serverless architecture for cost-efficient scaling
Project Structure
/frontend       → Angular application
/backend        → Node.js / Express API
/lambda         → AWS Lambda functions
/database       → DynamoDB configuration
/docs           → Screenshots, diagrams, and documentation
How to Run the Project (Local Development)
Prerequisites
Node.js (v18+ recommended)
Angular CLI
AWS CLI configured (for cloud deployment)
Steps

Clone the repository:

git clone https://github.com/your-username/cs470-project.git

Navigate to the frontend:

cd frontend
npm install
ng serve

Navigate to the backend:

cd ../backend
npm install
node server.js

Access the app:

http://localhost:4200
Cloud Deployment Summary
Frontend deployed to Amazon S3 static hosting
Backend replaced with AWS Lambda functions
API endpoints managed through API Gateway
Data stored in DynamoDB
Permissions managed using IAM roles and policies
Presentation



Skills Demonstrated
Full stack development (MEAN stack concepts)
Cloud architecture and deployment
Serverless application design
API development and integration
Database migration (MongoDB → DynamoDB)
Debugging and troubleshooting in cloud environments
Future Improvements
Implement authentication and user management
Add automated CI/CD pipeline
Improve UI/UX design
Enhance monitoring and logging with CloudWatch
Expand microservices architecture
