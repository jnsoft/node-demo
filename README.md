# node-demo
Web app using the Express.js framework

## setup
```
cd source
npm install
```
## run
```
docker build . -t node-demo:test
docker run -p 49160:8080 -d node-demo:test
docker ps
docker logs <container id>
docker exec -it <container id> /bin/bash (to enter container)
```

## test
```
curl -i localhost:49160
```

## exit
```
docker kill <container id>
```