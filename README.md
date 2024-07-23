
#  DevOps Assignment - Tenderd 

This documentation and configuration to help set up, build, and run microservices using Docker Compose, providing clear instructions for each service.

## Version
```
1.1.3
```

## Project structure: 
```

├── frontend-svc
│   ├── src/
│   │   ├── app.js
│   │   ├── views/
│   │   │   ├── index.ejs
│   │   │   ├── users.ejs
│   │   │   ├── orders.ejs
│   │   ├── routes/
│   │   │   ├── index.js
│   │   │   ├── users.js
│   │   │   ├── orders.js
│   ├── Dockerfile
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
├── user-svc
│   ├── src/
│   │   ├── app.js
│   ├── Dockerfile
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
├── order-svc
│   ├── src/
│   │   ├── app.js
│   ├── Dockerfile
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
├── docker-compose.yml
└── README.md

```

## Runing:
```
docker compose up --build
```

## Access:
Got to http://localhost:8080/ to browser the frontend page to checkout avaiable microservices. 