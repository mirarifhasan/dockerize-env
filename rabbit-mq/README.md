## Benefits :monocle_face:
Easy to use RabbitMQ in your local machine without taking any paid/unpaid server :wink:
Also, your data will be stored in the same path, where the `docker-compose.yaml` file exist. No worries on data loss :star_struck:.

## How to start
Run the followed cmd in your favourite terminal
```
$ docker-compose up -d
```

## Way to access RabbitMQ
* Goto [http://localhost:15672](http://localhost:15672)
* Connection URL `amqp://guest:guest@localhost:5672`
* Set username `guest`, password `guest`
* Click OK, and play with your RabbitMQ :sunglasses:

