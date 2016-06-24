docker-go-nginx
=========================
### prepare the app

```
make
```

### docker-compose

```
$ docker-compose up -d
```

## Connect Confirmation

```
$ curl -l http://$(docker-machine ip machine_name):18888
```
