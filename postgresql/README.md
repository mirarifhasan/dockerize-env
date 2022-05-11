## Benefits :monocle_face:
Easy to use PostgreSQL in your local machine :wink:
Also, your data will be stored in the same path, where the `docker-compose.yaml` file exist. No worries on data loss :star_struck:.

## How to start
Run the followed cmd in your favourite terminal
```
$ docker-compose up -d
```

## Way to access RabbitMQ
* Goto [http://localhost:5050](http://localhost:5050)
* Set email `admin@email.com`, password `admin`
* Click OK, and play with your pgAdmin4 :sunglasses:
* Now create a server with: `HOST=db | USERNAME=admin | PASSWORD=admin`
