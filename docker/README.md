# Docker container for the SSL Decoder

Build the docker image:
```bash
docker build -f docker/Dockerfile -t raymiiorg/ssl-decoder .
```

Run with docker:
```bash
docker run \
  --name ssl-decoder \
  -d \
  -p 80:80 \
  raymiiorg/ssl-decoder
```
