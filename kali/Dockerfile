# kali_container/Dockerfile
FROM kalilinux/kali-rolling

# Optional: Install common tools
RUN apt-get update && \
    apt-get install -y \
    iputils-ping \
    net-tools \
    nmap \
    tcpdump \
    curl \
    iproute2 \
    dnsutils \
    python3 \
    python3-pip \
    vim \
    git \    
    iw \
    aircrack-ng \
    wireless-tools

# Set default shell
CMD [ "bash" ]
