# Dockerized MERN Blog App

A full-stack blog application built with the **MERN stack** and containerized using **Docker**. The project uses React for the frontend, Node.js and Express for the backend, MongoDB for data storage, and Redis for caching.

---

## Project Overview

This project demonstrates how to build and run a full-stack web application using modern JavaScript technologies and Docker-based development.

The application allows users to create and view blog posts while using MongoDB as the primary database and Redis as a caching layer to improve performance.

---

## Key Features

- Full-stack MERN application
- React frontend
- Node.js and Express backend
- MongoDB database integration
- Redis caching layer
- REST API structure
- Dockerized application setup
- Docker Compose for running multiple services
- Organized backend folder structure with routes, models, services, middleware, and config

---

## Tech Stack

### Frontend
- React
- JavaScript
- HTML / CSS

### Backend
- Node.js
- Express.js
- REST APIs

### Database & Cache
- MongoDB
- Redis

### DevOps
- Docker
- Docker Compose

---

## Architecture

The application follows a simple full-stack architecture:

```text
React Frontend
      |
      v
Express / Node.js Backend
      |
      +------> MongoDB Database
      |
      +------> Redis Cache
