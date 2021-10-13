FROM cimg/node:16.10.0

COPY ../ app

WORKDIR /app

RUN yarn install

EXPOSE 80

CMD ["yarn", "start"]