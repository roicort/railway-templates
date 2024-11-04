# Usa la imagen base oficial de nginx
FROM nginx:1

# Copia el archivo de configuración personalizado en el contenedor
# Cambia "nginx.conf" por el nombre de tu archivo de configuración personalizado
COPY nginx.conf /etc/nginx/templates/default.conf.template

# Copia archivos de configuración adicionales, si es necesario
# COPY conf.d/ /etc/nginx/conf.d/

# Exponer el puerto 80 para el tráfico HTTP
EXPOSE 80

# Comando por defecto para ejecutar nginx en modo de primer plano
CMD ["nginx", "-g", "daemon off;"]
