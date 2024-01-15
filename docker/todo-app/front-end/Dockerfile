FROM node:16-alpine
EXPOSE 3001
WORKDIR /app/front-end
ADD node_modules.tar.gz  .
COPY . .
CMD ["npm", "start"]
