FROM python:3.10-slim

WORKDIR /app

# Creamos un archivo HTML básico de prueba
RUN echo "<h1>Hola desde tu microservicio Frontend</h1>" > index.html

# Levantamos un servidor web simple en el puerto 8090
CMD ["python", "-m", "http.server", "8090"]
