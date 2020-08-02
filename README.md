# Test of RabbitMQ with .Net Core 3.1

Project for testing message under protocol (AMQP), it has a Broker Message RabbitMQ on Docker Container and two project on .Net Core 3.1 (Send Message and Receive Message).

## Requirements

- Docker v19.03.12
- Docker-compose v1.24.1
- [SDK Framework .Net Core 3.1](https://dotnet.microsoft.com/download/dotnet-core/3.1)

## Run

- Execute docker-compose
```bash
docker-compose up -d
```

- Execute project Receive Message
```bash
cd Receive
dotnet run
```
    - Result:
```bash
cd Receive
dotnet run
```


- Execute project Send Message
```bash
cd Send
dotnet run
```

- Ready, 