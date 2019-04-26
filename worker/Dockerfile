FROM node:alpine
WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY ./ ./
# Dev defined development docker
#CMD ["npm", "run", "dev"]
# Production defined start script
CMD ["npm", "run", "start"]