FROM node:20.18.1-alpine

RUN apk add nano

COPY javascript.nanorc /usr/share/nano/javascript.nanorc
RUN echo "include /usr/share/nano/javascript.nanorc" >> ~/.nanorc

EXPOSE 3000

RUN mkdir ~/raw-docker-devcontainer

WORKDIR ~/raw-docker-devcontainer

CMD ["sleep", "infinity"]