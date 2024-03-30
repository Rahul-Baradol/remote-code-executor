# Decise

This is a microservice-based project that allows users to submit solutions to coding problems, with a primary focus on algorithms and data structures.

Currently the judge works with only C++ and Java solutions.

**It is ongoing project.**

## Overview

The project consists of the following components:

- Frontend: The frontend is written in Next.js and Tailwind CSS. It provides the user interface for submitting solutions and interacting with the system.

- Backend Services:
   - Authentication Service: This service handles user authentication and authorization.
   - Judge Service: The judge service is responsible for producing submitted solutions to the worker nodes, and storing the verdicts of the solutions.
   - Judger Nodes: These are the worker nodes that execute the submitted solutions and provide the results to the judge service.
   - Data Service: The data service uses a GraphQL server to handle data storage and retrieval of problems, submissions.

## Technologies Used

- Frontend: Next.js, Tailwind CSS
- Backend
  - Authentication, Judge: Express
  - Data Service: GraphQL
- Database: MongoDB