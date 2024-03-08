# NewRelicDemoApp

### clone the repo

```
git clone git@github.com:haihongren/NewRelicDemoApp.git
```

### build a docker image
```
cd NewRelicDemoApp
docker build -t newrelicdemoapp .
```

### run the app in docker container 
```
docker run -d -p 8181:8080 newrelicdemoapp
```

### test the app 
```
curl http://localhost:8181/weatherforecast

```