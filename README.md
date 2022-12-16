Run the docker container and the radar csv file is already mounted and being served on the container. 

```
    docker-compose up -d
    open http://localhost:8080
```

When you open the radar in the browser you can enter http://localhost:8080/files/tech_radar in the form and it will generate the radar.