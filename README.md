# Dockers Containers Challenge

Building a Multi-Container Application with Flask and Redis
## Objective

Create a multi-container application that consists of a simple Python Flask web app and a Redis database.
The Flask app should use Redis to store and retrieve data (a visit counter).

## Project Overview

This project demonstrates how to use Docker and Docker Compose to containerize multiple services and allow them to communicate with each other seamlessly.

Tech Stack:

Flask (Python web framework)

Redis (In-memory key-value store)

Docker & Docker Compose (Containerization and orchestration)

⚙️ Features
Flask Web Application

Route / → Displays a welcome message.

Route /count → Increments and displays a visit counter stored in Redis.

Redis Database

Acts as a persistent store for the visit counter.

Communicates with the Flask container via the internal Docker network.



