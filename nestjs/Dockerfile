FROM node:18-slim 
# debian

RUN apt update -y && \
    apt install -y procps && \
    npm install -g @nestjs/cli@9.4.2

WORKDIR /home/node/app

USER node

# ler o dispositivo nulo do linux
CMD [ "tail", "-f", "/dev/null" ]