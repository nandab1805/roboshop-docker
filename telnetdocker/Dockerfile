FROM ubuntu:latest

# Update package list and install Telnet
RUN apt-get update && apt-get install -y telnet

# Keep the container running by starting an interactive shell
CMD ["bash", "-c", "while true; do sleep 1; done"]