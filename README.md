# E-Commerce con Node.js, Express, React y MongoDB

Este proyecto es una plataforma de comercio electrónico que permite a los usuarios navegar por productos, gestionar un carrito de compras, y procesar pedidos. Está compuesto por un backend en **Node.js** con **Express** y una base de datos **MongoDB**, y un frontend desarrollado en **React**.
# **Características  Principales**

#### **Backend (Node.js + Express)**
- API REST para manejar productos, usuarios, carritos y pedidos.
- Autenticación y autorización mediante JSON Web Tokens (JWT).
- Control de acceso para usuarios con roles (cliente o administrador).

#### **Frontend (React)**
- Interfaz de usuario para explorar productos, gestionar el carrito y realizar pedidos.
- Diseño responsivo para dispositivos móviles y de escritorio.
- Gestión del estado con Context API o Redux.

#### **Base de Datos (MongoDB)**
- Colecciones para Users, Products, Categories, Cart y Orders.
- Esquemas con validaciones adecuadas para cada modelo.


## **Instalación**

### **Requisitos previos**
- Node.js (v16 o superior)
- npm (v8 o superior)
- MongoDB (local o MongoDB Atlas)
- Git

### **Pasos de instalación**

#### 1. Accede a la carpeta del backend:
 - Copiar código
- cd backend

#### Instala las dependencias:
- Copiar código
- npm install

### Crea un archivo .env en la raíz del backend con las siguientes variables:
- env: Copiar código
- PORT=5000MONGO_URI=mongodb+srv://<USUARIO>:<CONTRASEÑA>@cluster.mongodb.net/<BASE_DE_DATOS>JWT_SECRET=tu_secreto_jwt

Inicia el servidor:

- **npm run dev**

Crea un archivo .env en la raíz del frontend con las siguientes variables:
env
*Copiar código*  REACT_APP_API_URL=http://localhost:5000/api


**Inicia la aplicación de React:**
*npm start*

## Comandos Útiles
- npm run dev
- npm test
- npm start
- npm run build

# **Estructura del Proyecto**
 **e-commerce/**
- **backend/**
   -  models/
   - routes/
  -  controllers/
  - middleware/
  - server.js
    - .env

 - **frontend/**
   - src/
   - components/
     -  pages/ 
     -  App.js
     -  index.js
     - .env

    -  README.md
   -  package.json
