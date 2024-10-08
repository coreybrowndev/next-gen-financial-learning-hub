# Architecture

## Overview
This document provides an overview of the architecture for the [next-gen-financial-learning-hub] application. It outlines the main components and their interactions.

## Components

### 1. Client Side
- **Description**: The frontend application that users interact with.
- **Technologies**: React, Tailwind CSS
- **Responsibilities**:
  - User interface rendering
  - State management
  - Course selection
  - Course addition/Drop

### 2. Server Side
- **Description**: The backend service that handles business logic and data processing.
- **Technologies**: C#, .NET, JavaScript, MySQL
- **Responsibilities**:
  - RESTful API endpoints
  - Authentication
  - Data validation
  - Easier input of Data
  - Easier access to pictures and videos
  - Creating HTML templates styled with Tailwind, then converting them into JSON files.
  - Log-on system should utilize ASP.NET identity to avoid building a custom authentication        system.

### 3. Database
- **Description**: The database used to store application data.
- **Technologies**:
- **Responsibilities**:
  - Data storage
  - Query processing
  - Indexing
  - photo and video storage
  - storage off links 

# Microservice Architecture using Pipe and Filter Model

```mermaid
graph TD;
    A[Client] --> B[API Gateway];
    B --> C[Authentication Service];
    B --> D[Course Service];
    B --> E[Quiz Service];
    B --> F[Metrics Service];
    B --> G[Notification Service];
    
    D --> H[Version Control Service];
    E --> H;
    F --> H;
    
    D --> I[Database Service];
    E --> I;
    F --> I;

    subgraph Microservices
        C
        D
        E
        F
        G
        H
    end

    subgraph Data Storage
        I
    end


