# nginx-reverse-proxy

This is a example of nginx and docker.

## File structure
```
├───frontend_one
├───frontend_three
├───frontend_two
└───reverse-proxy-config
```

## Set up
```
$ cd nginx-reverse-proxy
$ docker-compose up -d
```

## Routes

| Container | Url |
| ----- | ---- |
| /  | [localhost:8001](http:/localhost:8001/)  |
| /frontend-one  | [localhost:8001](http:/localhost:8001/)  |
| /frontend-two  | [localhost:8002](http:/localhost:8002/)  |
| /frontend-three  | [localhost:8003](http:/localhost:8003/)  |

