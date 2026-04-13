FROM kalilinux/kali-rolling:latest

# Remove kali-linux-headless to keep the image small and stable
RUN apt-get update && apt-get install -y \
    hping3 \
    slowloris \
    net-tools \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
