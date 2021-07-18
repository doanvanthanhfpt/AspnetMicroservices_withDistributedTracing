# Microservices
Implementation is based on the online course on Microservices. It aims to show the working and communication amoing separate stand-alone Microservices with RabbitMQ, MassTransit, gRPC, MediatR and Ocelot.

It includes following packages:
<br> AutoMapper
<br> AutoMapper.Extensions.Microsoft.DependencyInjection
<br> Dapper
<br> FluentValidation
<br> FluentValidation.DependencyInjectionExtensions
<br> Grpc.AspNetCore
<br> IdentityServer4
<br> IdentityServer4.EntityFramework
<br> MassTransit
<br> MassTransit.AspNetCore
<br> MassTransit.RabbitMQ
<br> MediatR.Extensions.Microsoft.DependencyInjection
<br> Microsoft.EntityFrameworkCore.SqlServer
<br> Microsoft.EntityFrameworkCore.Design
<br> Microsoft.EntityFrameworkCore.Tools
<br> Microsoft.Extensions.Caching.StackExchangeRedis
<br> Microsoft.Extensions.Logging.Abstractions
<br> Microsoft.VisualStudio.Azure.Containers.Tools.Targets
<br> MongoDB.Driver
<br> MySql.EntityFrameworkCore
<br> Newtonsoft.Json
<br> Npgsql
<br> Ocelot
<br> Ocelot.Cache.CacheManager
<br> SendGrid
<br> Swashbuckle.AspNetCore

Ports:
<br> Catalog Api = 8000
<br> Basket Api = 8001
<br> Discount Api = 8002
<br> Discount Grpc = 8003
<br> Ordering Api = 8004
<br> Shopping Aggregator = 8005
<br> Web Application = 8006
<br> Ocelot Api Gateway = 8010
<br> Identify Server = 8015
<br> MongoDB Client = 3000
<br> pgAdmin4 = 5050 (admin@aspnetrun.com / Abcd1234)
<br> phpMyAdmin = 8080 (root / Abcd1234)
<br> Portainer = 9000 (admin / Abcd1234)
<br> RabbitMQ = 15672 (guest / guest)

To start, run below command: 
<br> docker-compose -f .\docker-compose.yml -f .\docker-compose.override.yml up -d
<br> and then browse http://localhost:8006/

To stop, run below command:
<br> docker-compose -f .\docker-compose.yml -f .\docker-compose.override.yml down
