# BanBajio App

Aplicación completa con Backend en Spring Boot, Frontend en Angular y Base de Datos MySQL. Todo orquestado con Docker Compose.

---

## Requisitos

- Docker ≥ 24
- Docker Compose integrado (v2)
- Node.js y Angular solo si deseas correr frontend en desarrollo

---

## Estructura del proyecto

BanBajio/
├─ backend/ # Spring Boot
│ ├─ Dockerfile
│ ├─ src/ ...
│ └─ pom.xml
├─ frontend/ # Angular
│ ├─ Dockerfile
│ ├─ src/ ...
│ └─ package.json
├─ bd/
│ └─ init/ # Scripts de inicialización de MySQL
├─ docker-compose.yml
└─ README.md


---

## Levantar la aplicación
s
1. Clona el repositorio:

```bash
git clone https://github.com/usuario/BanBajio.git
cd BanBajio

    Construye y levanta todos los servicios:

docker compose up --build -d# EntregableDockerizadoBanBajio
# EntregableDockerizadoBanBajio
# EntregableDockerizadoBanBajio
