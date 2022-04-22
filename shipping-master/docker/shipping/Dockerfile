FROM ubuntu:20.04



RUN apt-get update && \
apt install -y curl && \
apt-get install -y redis-server && \
apt-get clean



EXPOSE 6379



CMD ["curl", "redis-server"]
