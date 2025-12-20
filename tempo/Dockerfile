FROM grafana/tempo:latest

# Copy custom configuration
COPY tempo.yaml /etc/tempo.yaml

# Set the default command
CMD ["-config.file=/etc/tempo.yaml"]
