# Wraps the upstream multi-arch image so it operates on Supervisor's /data
# volume instead of the image-native /app/data. Supervisor builds this
# locally on each install; no addon-side CI required.

FROM ghcr.io/frahlg/forty-two-watts:v0.69.1

USER root
WORKDIR /data

CMD ["-config", "/data/config.yaml", "-web", "/app/web", "-drivers", "/app/drivers"]
