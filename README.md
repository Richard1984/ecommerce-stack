# ecommerce-stack

## Environment Variables
Set the following environment variables in your project's `.env` file:
```
DB_ROOT_PASSWORD=<your-db-root-password>
DB_USER=<your-db-user>
DB_PASSWORD=<your-db-password>
```

## Development
```bash
docker-compose -f docker-compose.dev.yml up -d --build
```

# Production
```bash
docker-compose -f docker-compose.yml up -d --build
```