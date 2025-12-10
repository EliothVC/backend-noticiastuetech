# Proyecto Noticias Tue Tech

Proyecto final para la asignatura de **Programación**.
Sitio web de Noticias ficticia, creado con Astro e implementado con Strapi y TailwindCSS.

## Configuración Para Iniciar el Proyecto

Luego de clonar el proyecto, se debe crear un archivo llamado `.env` en la carpeta raiz del proyecto (`/backend-noticiastuetech`), escribiendo lo siguiente dentro de su contenido:

```env

# Server
HOST=0.0.0.0
PORT=1337

# Secrets
APP_KEYS=5+FczTOG1eiv2CULYzJCSg==,8RF6flEqMZ9H3hV++Wld6Q==,3AHLDZvo0njrw1VG2w7hoA==,A18hvwKB9e7pFvz/W90rTw==
API_TOKEN_SALT=sfojK5GFNwauwkNy1lTMnQ==
ADMIN_JWT_SECRET=aicf3zpvPjdVzF2f0/5IzA==
TRANSFER_TOKEN_SALT=H6Tp4FlZz0Ut/t9K//G7AA==
ENCRYPTION_KEY=KSjRJT0VIWTsGXe0k2GpTg==

# Database
DATABASE_CLIENT=postgres
DATABASE_HOST=ep-weathered-bonus-acrdan6s-pooler.sa-east-1.aws.neon.tech
DATABASE_PORT=5432
DATABASE_NAME=strapibackend
DATABASE_USERNAME=neondb_owner
DATABASE_PASSWORD=npg_jicod01feBLX
DATABASE_SSL=true
DATABASE_FILENAME=
JWT_SECRET=9WUMVOiDUaQRCOb3KZrlzw==
```
Seguidamente de crear este archivo, se debe abrir una nueva terminal y ejecutar los siguientes comandos:

```npm install```

```npm run develop```

El proyecto correrá en ``http://localhost:1337`` que esta Hosteada en Render ```https://app-strapi-xfml.onrender.com```

Credenciales de Acceso:

admin@admin.com
contraseña: Admin1234

## Integrantes y Contribuciones

*Este proyecto fue desarrollado de manera colaborativa. A continuación se detalla la responsabilidad principal de cada uno:*

| Integrante                | Contribución Especifica                       |
| :------------------------ | :---------------------------------------------|
| Elioth Vargas (Lider del proyecto / Lider Frontend y backend)             | Desarrollo de la arquitectura de componentes, lógica de consumo de datos (API Fetch), implementación de rutas dinámicas, maquetación general y Configuración de Strapi.                        |
| Benjamin Vergara (Frontend / Responsive)      | Configuración responsive e Ideas de diseño de paginas    |
| Cristofer Marquez (Backend)          | Creación de Content Types e ir configurando los roles|
| Constanza Diaz (Backend)           | Generación y organización de todo el contenido dinámico del sitio.    |

## Frontend del Proyecto

El frontend de este proyecto se encuentra en el siguiente link:

``https://github.com/EliothVC/frontend-noticiastuetech.git``
