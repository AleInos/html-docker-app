# HTML + Docker + Nginx

Este proyecto es una mini app HTML que corre dentro de un contenedor Docker usando la imagen oficial de **nginx**.

##  Estructura

html-docker-app/
├── index.html
├── Dockerfile
└── README.md

##  Cómo usar

1. Clonar el repositorio:

git clone https://github.com/tu-usuario/html-docker-app.git
cd html-docker-app

2. Construir la imagen de Docker:
docker build -t html-docker-app .

3. Ejecutar el contenedor:
docker run -p 8080:80 html-docker-app

4. Acceder en el navegador:

Abre http://localhost:8080
