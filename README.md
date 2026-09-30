# Flask Redis App

A simple Flask web application connected to Redis using Docker Compose.

## Technologies

- Python
- Flask
- Redis
- Docker
- Docker Compose

## How It Works

The Flask application connects to Redis and stores a page visit counter.

Every time the page is refreshed, Redis increments the `visits` counter.

```text
Browser
   ↓
Flask Container :5000
   ↓
Redis Container :6379