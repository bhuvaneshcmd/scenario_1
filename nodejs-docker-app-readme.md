# Dockerized Node.js Application

## Prerequisites
- Docker installed
- Docker Compose (optional)

## Build and Run

### Using Docker CLI
```bash
# Build the Docker image
docker build -t nodejs-docker-app .

# Run the container
docker run -p 3000:3000 nodejs-docker-app
```

### Using Docker Compose (Optional)
```yaml
version: '3'
services:
  web:
    build: .
    ports:
      - "3000:3000"
```

## Accessing the Application
Open `http://localhost:3000` in your browser
