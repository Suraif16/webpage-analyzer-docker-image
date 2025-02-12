# Webpage Analyzer

This repository contains the Webpage Analyzer application, which includes a frontend and a backend. The application is containerized using Docker and can be easily started with `docker-compose`.

## Folder Structure

```
.
├── webpage-analyzer-backend  # Backend service
│   ├── .env                  # Backend environment variables
├── webpage-analyzer-frontend # Frontend service
│   ├── .env                  # Frontend environment variables
└── docker-compose.yml         # Docker Compose configuration
```

## Usage

1. Ensure Docker and Docker Compose are installed.
2. Run the application:
   ```sh
   docker-compose up
   ```
3. Stop the application:
   ```sh
   docker-compose down
   ```

Make sure `.env` files are correctly set up before starting.
