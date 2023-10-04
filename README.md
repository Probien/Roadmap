<div align="center" style="display:flex;flex-direction:column;">
    <img width="300" src="https://imgdb.net/storage/uploads/495cc30ad5b741033ede8604cb0ef566cb48b5685a252f34de460850dabb82f6.png" alt="Probien logo"/>
  <h2>Pawn Shop Web Application | Roadmap</h2>
  <p>
    <a target="_blank" href="https://crowdin.com/project/excalidraw">
      <img src="https://img.shields.io/badge/License-GPL%20v3-yellow.svg">
    </a>
        <a target="_blank" href="https://crowdin.com/project/excalidraw">
      <img src="https://img.shields.io/github/last-commit/ThePandaDevs/Probien-Backend">
    </a>
  </p>
</div>

## Monolith to Microservices
Probien is a project with the initial purpose of being a monolith and once finished, it will be split into a microservice architecture using GRPC or RabbitMQ with event driven architecture


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?
First, I had no idea how to structure the project, I come from java and have always used the MVC pattern to build services, then I decided to learn another type of desing so I create this project with domain based approach [(DDD)](https://airbrake.io/blog/software-design/domain-driven-design) and ports & adapters (Recomendations are welcome).

## Have a proposal? 
Submit a pull request for discussion

## Roadmap

- Phase 1 (Core service - Monolith)
  - JWT & SessionID Authentication :heavy_check_mark:
  - Authorization Based on Roles :heavy_check_mark:
  - Database logs :heavy_check_mark:
  - Transaction | CRUD Operations :heavy_check_mark:
  - HTTP Tests :heavy_check_mark:
  - Swagger Documentation :clock330:

- Phase 2 (Microservice 1, Serverless possibly)
  - Recover Password :clock330:
  - E-mail Notifications :clock330:

- Phase 3
  - Refactor code and bussiness logic (optional if not needed) :heavy_minus_sign:
  - Start frontend: :heavy_minus_sign:
    - (Microfrontend 1) Landing page (Next js) :heavy_minus_sign:
    - (Microfrontend 2) Administration application (React) :heavy_minus_sign:
    
- Proposals
  - (New microservice) Reports By Pawn Shop Branch :heavy_minus_sign:
  - (New microservice) Add employee payments :heavy_minus_sign:
  - Mobile App for customers :heavy_minus_sign:
    
