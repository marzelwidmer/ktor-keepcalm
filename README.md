# ktor-keepcalm

## Jib Build
```
./gradlew jibDockerBuild
```

## Docker Run
```
docker run --rm -p 8080:8080 ktor-keepcalm:0.0.1-SNAPSHOT
```

## Minikube Skaffold 
```
skaffold run
```


## Test with HTTPie
```
http :8080

HTTP/1.1 200 OK
Connection: keep-alive
Content-Length: 12
Content-Type: text/plain; charset=UTF-8
Date: Tue, 02 Mar 2021 20:51:06 GMT
Server: ktor-server-core/1.5.2
Vary: Origin
X-Engine: Ktor

HELLO WORLD!


```
