# In the Cloud
Demo "In the Cloud 1" Site as an HTTPD Container


## Build
```bash
docker build -t inthecloud1:latest .
```


## Run
```bash
docker container run -d -p80:80 inthecloud1:latest
```
