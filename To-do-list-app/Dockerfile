# FROM node:22-alpine
# WORKDIR /app
# COPY (package.json, yarn.lock) ./
# RUN yarn install --production
# COPY . .
# CMD ["node", "src/index.js"]
# EXPOSE 3000
FROM node:22-alpine
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]
EXPOSE 3000