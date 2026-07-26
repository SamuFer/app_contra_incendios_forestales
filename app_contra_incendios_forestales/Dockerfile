# 1. Construcción
FROM node:lts-alpine AS build
WORKDIR /app

# Copiamos archivos de configuración desde tu subcarpeta
COPY app_contra_incendios_forestales/package*.json ./
RUN npm install

# Copiamos el resto del código desde tu subcarpeta
COPY app_contra_incendios_forestales/ .
RUN npm run build

# 2. Servidor de estáticos con Nginx
FROM nginx:alpine
COPY --from=build /app/dist /usr/share/nginx/html

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]