FROM alpine:3.7

# packages 
RUN apk add --no-cache git cmake vim 

#clone pi-tools and pigpio into container. This repo will live under / folder 
RUN git clone https://github.com/raspberrypi/tools.git && \
    git clone https://github.com/joan2937/pigpio.git

ENTRYPOINT ash 

