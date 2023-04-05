FROM node:alpine

WORKDIR /app

COPY metrics.html .

EXPOSE 8080

CMD ["npx", "http-server", "-p", "8080"]