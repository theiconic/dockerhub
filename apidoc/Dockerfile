FROM node:lts-alpine

RUN npm install apidoc@0.17.7 -g

WORKDIR /app

ENTRYPOINT ["apidoc"]
CMD ["$@"]
