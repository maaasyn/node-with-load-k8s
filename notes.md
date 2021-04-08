### Budowanie obrazu aplikacji

```
docker build -t licencjat .
```

### Uruchamianie dokera

```
docker run -d --name licencjat -p 3000:3000 licencjat:latest
```

### loop strzelajacy do api

```
1..1000 | % {curl http://localhost:3000/stress/ram/15}
```