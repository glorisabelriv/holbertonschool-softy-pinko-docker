# Usa la última versión de la imagen de Nginx
FROM nginx:latest

# Copia los archivos del front-end a /var/www/html/softy-pinko-front-end
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copia el archivo de configuración de Nginx
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf