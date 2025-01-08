# Book Tool

This application is designed to showcase using GraphQL and AWS AppSync.

## Technical Requirements

    1.	GraphQL API:
    •	Define a schema with types for Book, Author, and Genre.
    •	Include relationships (e.g., a book belongs to an author and one or more genres).
    •	Support CRUD operations for all entities.
    •	Enable filtering and pagination for queries.
    2.	Backend (AWS AppSync):
    •	Use DynamoDB to store data for books, authors, and genres.
    •	Configure AppSync resolvers for querying, mutating, and managing the data.
    3.	Authentication:
    •	Use AWS Cognito for securing the API.
    •	Restrict access to specific mutations based on user roles (e.g., Admin vs. Viewer).
    4.	Validation and Error Handling:
    •	Validate input data using Zod.
    •	Implement clear error responses for invalid or unauthorized operations.
    5.	Infrastructure as Code (Terraform):
    •	Define resources for AppSync, DynamoDB, and Cognito using Terraform.
    6.	CI/CD:
    •	Set up GitHub Actions to automate testing and deployment.
