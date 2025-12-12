# Build stage
FROM node:18 AS build
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build

# Serve bằng Apache
FROM httpd:2.4
COPY --from=build /app/build /usr/local/apache2/htdocs/
EXPOSE 80
