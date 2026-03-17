Cats Gallery

Este proyecto consiste en una aplicación web desarrollada con React donde se muestra una galería con diferentes gatos.
En la página se puede ver la imagen de cada gato, una breve descripción, un video y un archivo PDF con información adicional.

Los archivos como imágenes, videos y documentos están guardados en Azure Blob Storage, y la aplicación los carga desde ahí para mostrarlos al usuario.

La aplicación también fue publicada en Vercel para que pueda ser vista desde internet.

Propósito del proyecto

La idea de este proyecto es crear una aplicación web que permita mostrar información utilizando archivos almacenados en la nube.

Con esto también se busca practicar algunos temas como:

uso de React

creación de componentes

consumo de archivos desde un almacenamiento en la nube

despliegue de aplicaciones web

Tecnologías utilizadas

Para desarrollar esta aplicación se utilizaron las siguientes herramientas y tecnologías:

React  para construir la interfaz de la aplicación

Vite  para crear y ejecutar el proyecto de forma rápida

Tailwind CSS para aplicar los estilos a la página

Azure Blob Storage  para almacenar imágenes, videos y documentos

Vercel  para publicar la aplicación

GitHub  para guardar y controlar las versiones del proyecto

Organización del proyecto

El proyecto está dividido en varias carpetas para organizar mejor el código.

src
│
├── components
│   ├── CatCard.jsx
│   └── CatDetail.jsx
│
├── hooks
│   └── useCats.js
│
├── pages
│   └── Gallery.jsx
│
├── services
│   └── catService.js
│
├── styles
│   └── gallery.css
│
├── App.jsx
└── main.jsx
Explicación de las carpetas

components  contiene los componentes que se reutilizan en la interfaz

hooks  incluye hooks personalizados de React

pages  donde están las páginas principales de la aplicación

services  funciones que ayudan a conectarse con Azure

styles  archivos de estilos de la aplicación

Funcionalidades

Dentro de la aplicación se pueden realizar varias acciones:

ver una galería de gatos

visualizar la imagen de cada gato

leer una descripción corta

ver un video relacionado

descargar un archivo PDF con información

Variables de entorno

Para que la aplicación pueda acceder a los archivos en Azure se usa una variable de entorno.

Se debe crear un archivo llamado .env en la raíz del proyecto con la siguiente variable:

VITE_SUPABASE_URL=https://fiihqbviqwucevygcunh.supabase.co

Esta dirección es la que permite cargar los archivos almacenados en Azure.

Cómo ejecutar el proyecto

Si se quiere ejecutar el proyecto en un computador local, se deben seguir estos pasos.

1. Clonar el repositorio
git clone https://github.com/JuliaanBeltraan/taller-supabase
2. Entrar a la carpeta del proyecto
cd cats-azure-main
3. Instalar las dependencias
npm install
4. Ejecutar el proyecto
npm run dev

Después de esto, el proyecto se abrirá en el navegador.

Generalmente en la dirección:

http://localhost:5173
Publicación del proyecto

La aplicación fue publicada utilizando Vercel, conectando el repositorio de GitHub.
De esta forma, cada vez que se realizan cambios y se suben al repositorio, el proyecto se actualiza automáticamente.

Autor

Julian Beltran

