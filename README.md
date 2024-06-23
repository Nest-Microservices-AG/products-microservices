<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# PRODUCT MICROSERVICE

## DEV MODE

1. Clone repository
2. install npm
3. Create file `.env` based on `.env.template`
4. Execute Prisma's migration `npx prisma migrate dev`
5. Run nats server `docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats`
6. Execute `npm run start:dev` 