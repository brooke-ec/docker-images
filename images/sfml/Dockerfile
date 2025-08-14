FROM --platform=$TARGETOS/$TARGETARCH ghcr.io/pterodactyl/yolks:alpine

LABEL org.opencontainers.image.source="https://github.com/nimajnebec/yolks"
LABEL org.opencontainers.image.licenses=MIT

USER root
RUN apk add --update --no-cache gcompat sfml
USER container