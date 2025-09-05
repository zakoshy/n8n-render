FROM n8nio/n8n:latest

# Set default user
USER root

# Create directory for n8n
RUN mkdir /home/node/.n8n

# Expose the n8n port
EXPOSE 5678

# Start n8n
CMD ["n8n"]
