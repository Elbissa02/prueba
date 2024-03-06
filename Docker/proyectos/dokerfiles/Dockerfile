FROM ubuntu
RUN apt update && apt install -yq --no-install-recommends \
    net-tools \
    iputils-ping \
    nano \
    curl
    
RUN useradd -m -d /home/karim -s /bin/bash karim
RUN echo 'karim:1234' |  chpasswd

