# FullStack Social Media App

![redsocial](https://user-images.githubusercontent.com/38227130/235321582-ec166365-353e-4b4b-9c97-d85a61c1d26c.png)


Proyecto Node.js, Express, React y MongoDB
Este es un proyecto web basado en Node.js, Express, React y MongoDB. La aplicación web permite a los usuarios crear cuentas, iniciar sesión, ver y editar su perfil, crear y editar publicaciones, y ver y comentar las publicaciones de otros usuarios.

Requisitos
Para ejecutar esta aplicación, necesitará tener instalado lo siguiente en su sistema:

Node.js
MongoDB
npm


# Configuración 

Clone este repositorio en su máquina local:

git clone https://github.com/digomic/redsocial

Navegue hasta el directorio raíz del proyecto:

cd redsocial
Instale las dependencias del servidor:

npm install
Navegue hasta el directorio de la aplicación de cliente:


cd client
Instale las dependencias del cliente:

npm install
Vuelva al directorio raíz del proyecto:


cd ..
Cree un archivo .env en el directorio raíz del proyecto con la siguiente información:
makefile

MONGO_URI=YOUR_MONGO_URI
SECRET_OR_KEY=YOUR_SECRET_KEY
Reemplace YOUR_MONGO_URI con la URI de su base de datos MongoDB y YOUR_SECRET_KEY con una clave secreta de su elección.

Ejecución
Para ejecutar la aplicación, abra dos terminales.

En la primera terminal, navegue hasta el directorio raíz del proyecto y ejecute el servidor:


npm run server
En la segunda terminal, navegue hasta el directorio de la aplicación de cliente y ejecute el cliente:

npm start

Contribución
Si desea contribuir a este proyecto, abra un problema o envíe una solicitud de extracción.

