# Foundations of Observability

### --- EVOLUTION OF APPLICATION ARCHITECTURE ---

# `MONOLITHIC ARCHITECTURE`

---

> User Interface
> 
> Business Logic
> 
> Data access layer ------------------------>  DATABASE

All services in one application 

User interface and business logic in one application

All services shared one database

> TO MAKE A CHANGE  $Entire Application$ was deployed
> 
> Incremental improvement was time consuming



# `MICROSERVICE ARCHITECTURE`

---

> User Interface 
> 
> /           |        \ 
> 
> Micro   Micro  Micro 
> 
> |           |          |
> 
> DB       DB      DB

Individual services

Each service has its own storage

UI and services are separate

>  Changescan be deployed without deploying the entiresoftware
> 
> Development on services can be done simultaneously
> 
> 

#### Previously we were using Agile or WaterFall methodology

### NOW WE ARE SHIFTING TO DEVOPS

> DevOps methodology helps us to understand the requirements and make the application architecture (plan , code , deploy, build , test) everything much faster way and continous way.

# Why are CI/CD and Microservices relevant to observability?

- #### Many SERVICES to monitor

- #### INTRA-SERVICE communications can fail

- #### More vulnerable to sercurity threats

- #### More changes are deployed








