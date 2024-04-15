# Building app
FROM node:18-alpine as build

WORKDIR /app

COPY package*.json ./

RUN npm ci --silent

COPY . ./

RUN npm run build -- --deploy-url /angular/

# Stargin NGINX
FROM nginx

COPY ./nginx.conf /etc/nginx/nginx.conf

COPY --from=build /app/dist/angular/browser /usr/share/nginx/html
