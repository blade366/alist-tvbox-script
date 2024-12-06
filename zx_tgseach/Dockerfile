FROM alpine:3.21

ARG TARGETPLATFORM

COPY --chmod=755 $TARGETPLATFORM/tgsearch /app/tgsearch

ENTRYPOINT [ "/app/tgsearch" ]
