Proyecto CATS – Catálogo de Gatos
DESCRIPCION
El proyecto CATS es una aplicación web donde se pueden ver diferentes razas de gatos junto con información sobre cada una. La idea del proyecto es mostrar imágenes, videos y una ficha técnica con datos importantes de cada raza.
La aplicación permite navegar por un catálogo de gatos y conocer características como su apariencia, comportamiento o cuidados. Para esto se utilizaron varias herramientas de desarrollo web y servicios en la nube de Microsoft Azure.

COMO FUNCIONA EL PROYECTO

La aplicación está organizada en diferentes partes para que el sistema funcione de forma ordenada.
Primero está la parte visual, que es lo que ve el usuario cuando entra a la página. Esta parte fue hecha con React, y es donde se muestran las imágenes de los gatos, los videos y la información de cada raza.
Luego está la parte donde se gestionan los recursos que usa la aplicación, como las imágenes, videos y documentos. Estos archivos se almacenan en la nube para que la aplicación pueda cargarlos cuando el usuario los necesite.
Finalmente está la base de datos, donde se guarda la información relacionada con las razas de gatos.

TECNOLOGIAS UTILIZADAS
Para desarrollar este proyecto se utilizaron varias herramientas y tecnologías, entre ellas:
React, para crear la interfaz de la página web.
Node.js y NPM, para manejar las dependencias del proyecto.
Git y GitHub, para guardar y controlar los cambios del código.
Azure App Service, para publicar la aplicación en internet.
Azure Blob Storage, para almacenar las imágenes, videos y archivos PDF.
Azure SQL Database, para manejar la base de datos.
GitHub Actions, para automatizar el despliegue del proyecto.
ALMACENAMIENTO DE IMAGENES Y ARCHIVOS

Las imágenes, videos y fichas técnicas se guardan en Azure Blob Storage, que es un servicio de almacenamiento en la nube.
Dentro del contenedor llamado cats se encuentran los diferentes archivos que utiliza la aplicación. Estos archivos se pueden cargar desde la página web mediante enlaces, permitiendo mostrar el contenido multimedia sin afectar el funcionamiento de la aplicación.

DESPLIEGUE DE LA APLICACION

La aplicación fue publicada utilizando Azure App Service, lo que permite que la página esté disponible en internet y pueda ser abierta desde cualquier navegador.
De esta manera, el catálogo de gatos puede ser consultado en línea y acceder a todos los recursos multimedia asociados.

BASE DE DATOES
Para almacenar la información del proyecto se utilizó Azure SQL Database. En esta base de datos se guardan los datos relacionados con las razas de gatos, como su nombre, descripción, colores y otros detalles.
Esto permite organizar la información y facilitar su consulta dentro de la aplicación.

REPOSITORIO

Todo el código del proyecto fue subido a GitHub, donde se encuentra organizado el proyecto junto con los archivos necesarios para su funcionamiento.

El repositorio permite llevar un control de los cambios realizados durante el desarrollo del proyecto.

Autor

Proyecto realizado como parte de una actividad académica relacionada con el uso de Azure y desarrollo web.
