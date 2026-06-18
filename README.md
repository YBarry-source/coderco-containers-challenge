# coderco-containers-challenge

## Overview

This project demonstrates a multi-container application using Docker Compose.

The application consists of:

* A Python Flask web application
* A Redis database
* Docker Compose for orchestration

## Features

### Home Page

Navigate to:

http://localhost:5000

Displays a welcome message.

### Visit Counter

Navigate to:

http://localhost:5000/count

Each visit increments a counter stored in Redis.

## Technologies Used

* Python
* Flask
* Redis
* Docker
* Docker Compose

## Run the Application

Clone the repository and run:

```bash
docker compose up --build
```

Access the application at:

http://localhost:5000

## Project Structure

coderco-containers-challenge/

├── docker-compose.yml

├── app/
│   ├── app.py
│   ├── Dockerfile
│   └── requirements.txt

└── redis/
├── Dockerfile
└── redis.conf
