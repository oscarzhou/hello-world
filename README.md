# hello-world
docker-compose hello world web server


```
git checkout https://github.com/oscarzhou/hello-world.git
docker-compose up
# Ping http://localhost:5566
```



Upload the new build docker image

```
cd ./nginx-hello && docker build -t oscarzhou/nginx-hello:1 -f ./Dockerfile . && docker image push oscarzhou/nginx-hello:1
```