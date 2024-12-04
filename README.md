
# Crypto Exchange Application

## Overview
The **Crypto Exchange Application** is a simple web-based platform that fetches and displays cryptocurrency exchange rates for 10 predefined cryptocurrencies. It is built with **Laravel** (backend) and **React** (frontend), and uses **Docker** for containerized development and deployment.

## Features
- **Frontend**: Built with React to provide a dynamic, user-friendly interface.
- **Backend**: Developed using Laravel to handle API requests and business logic.
- **Live Updates**: Fetches cryptocurrency exchange rates every 10 seconds.
- **Dockerized Environment**: Uses Docker Compose for seamless development and deployment.

---

## Tech Stack
- **Frontend**: React with Vite
- **Backend**: Laravel (PHP 8.4)
- **Database**: MySQL 8.1
- **Web Server**: Nginx
- **Containerization**: Docker and Docker Compose

---

## Project Structure
```
/crypto-exchange
├── /frontend            # React app
├── /src                 # Laravel app
├── docker-compose.yml   # Docker setup for the project
├── Dockerfile           # Dockerfile for Laravel (backend)
├── nginx.conf           # Nginx configuration
└── README.md            # Project documentation
```
