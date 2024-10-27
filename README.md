# GuruSup Clone - Automated Customer Support Agent

Este proyecto es un clon de GuruSup, un agente de soporte al cliente automatizado diseñado para responder tickets y consultas de usuarios de manera eficiente. La aplicación está construida con un backend en Python y un frontend en React, integrando agentes de IA y LLMs (como CodeGPT y Mistral) para mejorar la experiencia de soporte al cliente.

## Estructura del Proyecto

La estructura del proyecto está organizada para separar claramente el frontend (React) y el backend (Python), de modo que puedan interactuar a través de una API REST.



## Requisitos Previos

1. Python 3.13 y Node.js
2. Instalar dependencias de backend: `pip install -r backend/requirements.txt`
3. Instalar dependencias de frontend: `npm install` en la carpeta `frontend`

## Instalación

1. Clonar el repositorio.
2. Configurar el archivo `.env` en el backend con las variables de entorno necesarias para la conexión a la base de datos, configuraciones de autenticación y las claves de los LLMs (por ejemplo, Mistral).
3. Iniciar el backend: Navegar a la carpeta `backend` y ejecutar `python app/main.py`
4. Iniciar el frontend: Navegar a la carpeta `frontend` y ejecutar `npm start`

## Funcionalidades

1. **Sistema de Tickets**: Los usuarios pueden enviar consultas y tickets.
2. **IA para Respuestas**: Usando LLMs (Mistral o CodeGPT), el sistema genera respuestas automáticas para los tickets.
3. **Notificación de Correo**: El sistema monitorea el correo electrónico y notifica cuando se recibe una nueva consulta.
4. **Almacenamiento en Base de Datos**: Los datos de los tickets y respuestas se almacenan para referencia futura.

## Tecnologías Utilizadas

- **Backend**: Python, FastAPI/Django, Mistral, CodeGPT
- **Frontend**: React, Axios para solicitudes HTTP
- **Base de Datos**: PostgreSQL/MySQL
- **Notificación de Correo**: Integración de servicio de correo (ej: Gmail API)

## Contribución

Para contribuir a este proyecto:

1. Haz un fork del repositorio.
2. Crea una rama con tu función: `git checkout -b feature/nueva-funcion`
3. Realiza el commit de tus cambios: `git commit -m 'Añadir nueva función'`
4. Haz un push a la rama: `git push origin feature/nueva-funcion`
5. Abre un Pull Request.

---

Este proyecto es una excelente forma de aprender a construir aplicaciones modernas con una arquitectura full-stack, integrando tecnologías de IA para mejorar la experiencia de usuario en el soporte al cliente.
