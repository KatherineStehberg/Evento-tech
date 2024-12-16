# Evento Tech

¡Bienvenido al repositorio del proyecto **Evento Tech**! Este proyecto fue desarrollado como parte de la prueba de salida del curso de UX/UI en Talento Digital. La temática del proyecto gira en torno a la creación de una plataforma digital para gestionar y promocionar eventos tecnológicos de manera efectiva.

## Objetivo del proyecto

El propósito principal de **Evento Tech** es proporcionar una experiencia fluida y atractiva tanto para los organizadores como para los asistentes de eventos tecnológicos. La plataforma permite explorar eventos, gestionar inscripciones y facilitar la interacción entre los participantes.

## Características principales

- **Gestión de eventos**: Los organizadores pueden crear, editar y eliminar eventos.
- **Exploración de eventos**: Los usuarios pueden buscar eventos por categoría, fecha y ubicación.
- **Registro e inicio de sesión**: Permite a los usuarios registrarse y acceder a funciones personalizadas.
- **Interfaz intuitiva**: Diseño centrado en el usuario para una experiencia accesible y atractiva.

## Tecnologías utilizadas

### Diseño UX/UI
- **Figma**: Herramienta para wireframes, prototipos y diseño de interfaz.
- **Adobe Illustrator**: Creación de elementos gráficos y diseño visual.

### Frontend
- **React**: Biblioteca para construir la interfaz de usuario.
- **Vite**: Herramienta para desarrollo rápido y eficiente.
- **CSS3**: Para diseño responsivo y estilización.

### Backend
- **Node.js**: Para manejar la lógica del servidor.
- **Express**: Framework para crear las APIs necesarias.
- **MongoDB**: Base de datos para almacenar información sobre usuarios y eventos.

## Estructura del proyecto

```
Evento-tech/
├── frontend/
│   ├── src/
│   │   ├── components/  # Componentes reutilizables
│   │   ├── pages/       # Páginas principales de la aplicación
│   │   ├── App.jsx      # Componente principal
│   │   └── styles.css   # Estilos generales
├── backend/
│   ├── server.js        # Archivo principal del servidor
│   ├── routes/          # Rutas de la API
│   ├── controllers/     # Lógica del servidor
│   ├── models/          # Modelos de datos
│   └── config/          # Configuración de la base de datos
├── .env                 # Variables de entorno
├── package.json         # Configuración de dependencias
└── README.md            # Documentación del proyecto
```

## Instalación y configuración

### Requisitos previos

1. Node.js (v18 o superior).
2. MongoDB.
3. Git.

### Pasos para la instalación

1. Clona este repositorio:

   ```bash
   git clone https://github.com/KatherineStehberg/Evento-tech.git
   cd Evento-tech
   ```

2. Configura las variables de entorno en un archivo `.env`:

   ```
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/eventotech
   JWT_SECRET=clave_secreta
   ```

3. Instala las dependencias del frontend y backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. Inicia el servidor y el cliente:

   **Backend:**
   ```bash
   npm start
   ```

   **Frontend:**
   ```bash
   cd ../frontend
   npm run dev
   ```

5. Accede a la aplicación en tu navegador:

   ```
   http://localhost:5173
   ```

## Contribuciones

Este proyecto fue diseñado como parte de una prueba educativa, pero las contribuciones siempre son bienvenidas. Si deseas colaborar, crea un *fork* del repositorio, realiza tus cambios y envía un *pull request*.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

¡Gracias por visitar **Evento Tech**! 🚀
