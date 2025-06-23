# Product Management App

This repository contains a backend and frontend application for product management, built with Spring Boot (backend) and React (frontend). The application uses PostgreSQL as the database.

---

## Prerequisites

- Docker and Docker Compose installed
- Git installed

---

## Setup

1. **Clone the repository**

```bash
git clone --recurse-submodules https://github.com/Oumaymaazmi/crud-task-devstack.git
cd crud-task-devstack

```


## Create a .env file

2. **Create a .env file**

Create a file named .env in the root directory (same place as docker-compose.yml) with the following content:

```env
# PostgreSQL database settings
POSTGRES_DB=postgres
POSTGRES_USER=user_name
POSTGRES_PASSWORD=user_password
```
Replace the values with your preferred database username and password.

## Running the application

Use Docker Compose to build and start all services:

```bash
docker-compose up --build
```

This will start:

-  PostgreSQL database on port 5432
-  Backend API on port 8080
-  Frontend React app on port 3000



## Access the application

  - Frontend UI: http://localhost:3000

  - Backend API: http://localhost:8080

