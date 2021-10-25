# Dockerfile
```Dockerfile
FROM paloaltonetworks/minemeld

LABEL org.opencontainers.image.authors="piere@woehl.email"
LABEL org.opencontainers.image.source="https://github.com/pierew/minemeld-docker"

COPY minemeldlocal.yml /opt/minemeld/local/prototypes/minemeldlocal.yml
```
