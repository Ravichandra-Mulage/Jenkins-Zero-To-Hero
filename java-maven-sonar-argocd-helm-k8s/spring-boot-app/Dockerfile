
FROM maven:3.9.6-eclipse-temurin-17

# Install required tools
RUN apt-get update && \
    apt-get install -y docker.io git && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

# Keep the container alive for Jenkins
CMD ["sleep", "infinity"]
