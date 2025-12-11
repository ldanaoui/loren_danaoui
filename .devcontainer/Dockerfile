# Use the Default Linux Universal dev container image as the base
FROM mcr.microsoft.com/devcontainers/universal:2

# Update package lists
RUN sudo apt-get update

# Ensure Python tools are available
RUN sudo apt-get install -y python3-pip python3-venv

# Install Flask for backend development
RUN python3 -m pip install --no-cache-dir flask

# Install Vue.js CLI for frontend development
RUN npm install -g @vue/cli
