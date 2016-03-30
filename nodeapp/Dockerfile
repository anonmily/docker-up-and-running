FROM anonmily/node:latest
MAINTAINER Michelle Liu <michelle@michelleliu.io>
COPY node_modules /src/node_modules
EXPOSE 3000
WORKDIR /src
COPY bin /src/bin
COPY routes /src/routes
COPY views /src/views
COPY app.js package.json /src/
CMD ["node /src/bin/www"]