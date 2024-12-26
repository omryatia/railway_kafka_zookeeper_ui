FROM confluentinc/cp-zookeeper:latest

# Create the data directory
RUN mkdir -p /var/lib/zookeeper

# Expose Zookeeper port
EXPOSE 2181

# Set environment variables
ENV ZOOKEEPER_CLIENT_PORT=2181
