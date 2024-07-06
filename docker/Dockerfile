# Use an official Grafana image as a base
FROM grafana/grafana:latest

# Copy custom configuration files if needed
# Example:
# COPY ./custom.ini /etc/grafana/grafana.ini

# Expose Grafana port
EXPOSE 3000

# Set Grafana environment variables if needed
# Example:
# ENV GF_SECURITY_ADMIN_PASSWORD=admin

# You can add more environment variables or commands here as needed

# Start Grafana server
CMD ["grafana-server", "--config=/etc/grafana/grafana.ini"]
