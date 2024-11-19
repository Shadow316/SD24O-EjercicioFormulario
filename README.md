# Actividad en Clase - UEA de Sistemas Distribuidos

Durante la clase del **Martes 19 de noviembre de 2024** en la UEA de **Sistemas Distribuidos**, se realizó la siguiente práctica con las siguientes indicaciones:

## Instrucciones

### 1. Crear un formulario HTML para registrar usuarios

El formulario debe permitir el registro de los siguientes parámetros:

- **Nombre** (Campo de texto)
- **Dirección** (Campo de texto)
- **Fotografía** (Campo de archivo para subir una imagen)
- **VIP** (Checkbox que indique si el usuario es VIP)

### 2. Crear un servidor con **FastAPI** para atender la petición POST

El servidor debe recibir los datos enviados desde el formulario y realizar las siguientes acciones:

- Imprimir los datos recibidos en la terminal.
- Guardar las fotografías en el directorio raíz del servidor, en las siguientes carpetas:
  - **fotos-usuarios-vip**: Para almacenar las fotos de los usuarios VIP.
  - **fotos-usuarios**: Para almacenar las fotos de los usuarios que no son VIP.

### 3. Almacenar el código en un repositorio de GitHub

El código debe ser almacenado en un repositorio público de GitHub con el nombre `SD24O-EjercicioFormulario`. Asegúrate de incluir un enlace al repositorio en el README.

## Requisitos

- HTML
- FastAPI
- Python (con dependencias necesarias como `fastapi`, `uvicorn`, `pydantic`, etc.)

## Estructura del Proyecto

```plaintext
SD24O-EjercicioFormulario/
│
├── api.py                     # Código del servidor FastAPI
├── test.html                  # Formulario HTML para registrar usuarios
├── .gitignore                 # Ignora archivos irrelevantes
└── README.md                  # Este archivo
