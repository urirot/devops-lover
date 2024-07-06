FROM node:20-alpine AS build

WORKDIR /app
COPY . .

RUN yarn
RUN yarn build

FROM nginx:1.27-alpine AS deploy

WORKDIR /usr/share/nginx/html
RUN rm -rf ./*
COPY --from=build /app/public .

ENTRYPOINT [ "nginx", "-g", "daemon off;" ]

