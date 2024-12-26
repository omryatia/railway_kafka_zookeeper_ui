FROM confluentinc/cp-kafka:latest

# Create the data directory
RUN mkdir -p /var/lib/kafka

# Expose Kafka port
EXPOSE 9092

# Set environment variables
ENV KAFKA_ZOOKEEPER_CONNECT=zookeeper:2181
ENV KAFKA_ADVERTISED_LISTENERS=PLAINTEXT://kafka:9092
ENV KAFKA_OFFSETS_TOPIC_REPLICATION_FACTOR=1
