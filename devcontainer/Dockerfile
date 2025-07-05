ARG VARIANT=ubuntu-22.04
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

# نثبت AWS CLI
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && \
    unzip awscliv2.zip && \
    sudo ./aws/install && \
    rm -rf awscliv2.zip awscliv2
