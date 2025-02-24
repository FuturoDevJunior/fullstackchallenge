Fullstack Challenge

[Português | English | Español]
Português
Sobre o Projeto

O Fullstack Challenge é uma aplicação completa desenvolvida como parte de um desafio técnico para demonstrar habilidades em desenvolvimento fullstack. Este projeto integra um backend robusto com FastAPI, um frontend interativo com React, um banco de dados MongoDB e um serviço de armazenamento S3 mockado com LocalStack, tudo orquestrado com Docker Compose. O objetivo é criar uma solução escalável para gerenciamento de produtos, categorias e pedidos, com upload de imagens e uma interface amigável.
Tecnologias Utilizadas

    Backend: Python, FastAPI, PyMongo, Boto3
    Frontend: React, Node.js
    Banco de Dados: MongoDB
    Infraestrutura: Docker, Docker Compose, LocalStack (S3)
    Controle de Versão: Git, GitHub

Como Executar

    Pré-requisitos:
        Docker e Docker Compose instalados.
        Git instalado.

    Passos:
    bash

# Clone o repositório
git clone https://github.com/FuturoDevJunior/fullstackchallenge.git

# Entre no diretório do projeto
cd fullstackchallenge

# Suba os serviços com Docker Compose
docker-compose up --build

# Acesse o backend (API) em: http://localhost:8000/docs
# Acesse o frontend em: http://localhost:3000

# (Opcional) Popule o banco de dados com dados iniciais
docker exec -it fullstackchallenge-backend-1 python /app/scripts/populate_db.py

Parar os serviços:
bash

    docker-compose down

Estrutura do Projeto

    backend/: Contém a API FastAPI com endpoints para gerenciamento de produtos.
    frontend/: Interface React com rotas para produtos, categorias, pedidos e dashboard.
    docker-compose.yml: Orquestração dos serviços (backend, frontend, MongoDB, LocalStack).

Habilidades Demonstradas

    Desenvolvimento fullstack com integração frontend-backend.
    Uso de containers para deploy consistente (Docker).
    Gerenciamento de banco de dados NoSQL (MongoDB).
    Integração com serviços de armazenamento (S3 via LocalStack).
    Controle de versão e boas práticas com Git.

Contato

Quer discutir o projeto ou oportunidades? Entre em contato comigo:

    GitHub: FuturoDevJunior
    [Insira seu e-mail ou LinkedIn aqui]

English
About the Project

The Fullstack Challenge is a complete application developed as part of a technical challenge to showcase fullstack development skills. This project integrates a robust backend with FastAPI, an interactive frontend with React, a MongoDB database, and a mocked S3 storage service using LocalStack, all orchestrated with Docker Compose. The goal is to deliver a scalable solution for managing products, categories, and orders, featuring image uploads and a user-friendly interface.
Technologies Used

    Backend: Python, FastAPI, PyMongo, Boto3
    Frontend: React, Node.js
    Database: MongoDB
    Infrastructure: Docker, Docker Compose, LocalStack (S3)
    Version Control: Git, GitHub

How to Run

    Prerequisites:
        Docker and Docker Compose installed.
        Git installed.

    Steps:
    bash

# Clone the repository
git clone https://github.com/FuturoDevJunior/fullstackchallenge.git

# Navigate to the project directory
cd fullstackchallenge

# Start the services with Docker Compose
docker-compose up --build

# Access the backend (API) at: http://localhost:8000/docs
# Access the frontend at: http://localhost:3000

# (Optional) Populate the database with initial data
docker exec -it fullstackchallenge-backend-1 python /app/scripts/populate_db.py

Stop the services:
bash

    docker-compose down

Project Structure

    backend/: Contains the FastAPI backend with endpoints for product management.
    frontend/: React frontend with routes for products, categories, orders, and dashboard.
    docker-compose.yml: Orchestrates the services (backend, frontend, MongoDB, LocalStack).

Demonstrated Skills

    Fullstack development with frontend-backend integration.
    Containerized deployment using Docker.
    NoSQL database management (MongoDB).
    Integration with storage services (S3 via LocalStack).
    Version control and best practices with Git.

Contact

Interested in discussing the project or opportunities? Reach out to me:

    GitHub: FuturoDevJunior
    [Insert your email or LinkedIn here]

Español
Sobre el Proyecto

El Fullstack Challenge es una aplicación completa desarrollada como parte de un desafío técnico para demostrar habilidades de desarrollo fullstack. Este proyecto integra un backend robusto con FastAPI, un frontend interactivo con React, una base de datos MongoDB y un servicio de almacenamiento S3 simulado con LocalStack, todo orquestado con Docker Compose. El objetivo es ofrecer una solución escalable para la gestión de productos, categorías y pedidos, con carga de imágenes y una interfaz amigable.
Tecnologías Utilizadas

    Backend: Python, FastAPI, PyMongo, Boto3
    Frontend: React, Node.js
    Base de Datos: MongoDB
    Infraestructura: Docker, Docker Compose, LocalStack (S3)
    Control de Versión: Git, GitHub

Cómo Ejecutar

    Requisitos Previos:
        Docker y Docker Compose instalados.
        Git instalado.

    Pasos:
    bash

# Clonar el repositorio
git clone https://github.com/FuturoDevJunior/fullstackchallenge.git

# Ingresar al directorio del proyecto
cd fullstackchallenge

# Iniciar los servicios con Docker Compose
docker-compose up --build

# Acceder al backend (API) en: http://localhost:8000/docs
# Acceder al frontend en: http://localhost:3000

# (Opcional) Poblar la base de datos con datos iniciales
docker exec -it fullstackchallenge-backend-1 python /app/scripts/populate_db.py

Detener los servicios:
bash

    docker-compose down

Estructura del Proyecto

    backend/: Contiene el backend FastAPI con endpoints para la gestión de productos.
    frontend/: Interfaz React con rutas para productos, categorías, pedidos y dashboard.
    docker-compose.yml: Orquesta los servicios (backend, frontend, MongoDB, LocalStack).

Habilidades Demostradas

    Desarrollo fullstack con integración frontend-backend.
    Despliegue en contenedores con Docker.
    Gestión de bases de datos NoSQL (MongoDB).
    Integración con servicios de almacenamiento (S3 vía LocalStack).
    Control de versión y buenas prácticas con Git.

Contacto

¿Quieres hablar sobre el proyecto o oportunidades? Contáctame:

    GitHub: FuturoDevJunior
    [Inserta tu correo o LinkedIn aquí]

Status e Badges

GitHub Repo stars GitHub forks GitHub issues GitHub pull requests
Formatações Avançadas

Adicione interações avançadas ao seu readme, como gráficos, gifs, e mais, para torná-lo mais envolvente.
Contribuição

Ajude a tornar este projeto ainda melhor! Leia como contribuir aqui.
