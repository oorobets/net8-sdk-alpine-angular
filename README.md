# How to create new an image for new Angular version

1. Build image:
```bash
docker build --build-arg AngularVersion=<version> -t oorobets/net8-sdk-alpine-angular:<version> .
```

2. Push image:
```bash
docker push oorobets/net8-sdk-alpine-angular:<version>
```
