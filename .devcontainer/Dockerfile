FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04

# Installation de QEMU et des outils nécessaires
RUN apt-get update && apt-get install -y \
    qemu-system-x86 \
    qemu-utils \
    net-tools \
    iproute2 \
    && apt-get clean -y
