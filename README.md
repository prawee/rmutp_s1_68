# Prisma

Prawee Wongsa

## Required
- Git
- Docker & Docker Compose
- PostgreSQL
- Node.js
- Prisma

## Running
### Database
```
docker-compose up -d
```
### Schema
```
npx prisma generate
npx prisma studio
```

## Develop
### First time
```bash
npx prisma init --datasource-provider postgresql
npx prisma generate
npx prisma db push
```