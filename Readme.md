# docker-compose-application

Demo application using nginx as a reverse proxy to load balance accross 2 web services and a databse. This shall spin up 4 conatiners:
```
2 WebServer Containers
1 Database  Container
1 Nginx LoadBalancer Container
```

To Start in Backend Mode:

```
sudo docker-compose up -d
```

To Start in Frontend Mode:

```
sudo docker-compose up
```

To Stop:

```
sudo docker-compose stop
```

In order to verify navigate to localhost:8000 on your browser. Refresh the page few times and you will see the load balancer navigating between Server1 & Server2. 
