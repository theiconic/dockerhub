FROM node:lts-alpine

RUN npm install apidoc@0.17.7 -g

WORKDIR /app

RUN echo 123

ENTRYPOINT ["apidoc"]
CMD ["$@"]
