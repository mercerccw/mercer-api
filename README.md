# Mercer Systems API

#### JDK: AdoptOpenJDK v11.0.11-9

To create Docker image run 
```
docker build -t mercer-systems/mercer-api .
```

To run deploy the application locally, run 
```
docker run -p 8080:8080 mercer-systems/mercer-api
```

To test a REST endpoint, navigate to http://localhost:8080/greeting?name=John
