# Run the container

```bash
docker build -t televolution_deployment .
docker run --privileged -p 8000:8000 -p 8001:8001 -p 3000:3000 -p 3001:3001 televolution_deployment
```

docker run -it --privileged televolution_deployment /bin/bash