### DockTree

DockTree es una plataforma web diseñada para centralizar la gestión de tus contenedores (CT) y la configuración del servidor en un solo lugar. Administra tu infraestructura de manera rápida, intuitiva y sencilla sin necesidad de lidiar constantemente con la terminal. 

### Características principales

* **Centralización completa:** Visualiza y gestiona todos tus contenedores desde un único panel web.
* **Administración ágil:** Apaga, enciende, reinicia o edita la configuración de tus CT con unos pocos clics.
* **Configuración del servidor:** Modifica parámetros clave del sistema anfitrión de forma segura y simplificada.
* **Interfaz intuitiva:** Diseñada para ofrecer una experiencia de usuario fluida y sin complicaciones.

### Requisitos previos

Antes de instalar DockTree, asegúrate de cumplir con los siguientes requisitos en tu servidor: 

* Docker / LXC (o el motor de contenedores que utilices)
* Node.js (versión 18 o superior) / Python (según tu backend)
* Acceso de administrador (root o privilegios sudo) para la gestión del servidor

### Instalación rápida

1. **Clona el repositorio:** 

bash

git clone https://github.com/Nindex120/Docktree.git
cd docktree

Usa el código con precaución.
2. **Instala las dependencias:** 

bash

npm install 

Usa el código con precaución.
3. **Configura las variables de entorno:**
Crea un archivo .env en la raíz del proyecto basándote en .env.example y ajusta los parámetros de tu servidor.
4. **Inicia la aplicación:** 

bash

npm run start

Usa el código con precaución.

### Hoja de ruta (Roadmap)

* [ ] Panel de estadísticas en tiempo real (CPU, RAM, Almacenamiento).
* [ ] Sistema de alertas y notificaciones (Email / Telegram).
* [ ] Soporte para múltiples servidores anfitriones.

### Contribuciones

Las contribuciones son lo que hacen que la comunidad de código abierto sea un lugar increíble para aprender, inspirar y crear. Cualquier contribución que hagas será muy agradecida. 

1. Haz un Fork del proyecto.
2. Crea tu rama de funciones (git checkout -b feature/AmazingFeature).
3. Realiza tus cambios y haz un Commit (git commit -m 'Add some AmazingFeature').
4. Sube la rama (git push origin feature/AmazingFeature).
5. Abre un Pull Request.

### Licencia

Distribuido bajo la Licencia AGPLv3. Consulta el archivo LICENSE para obtener más información.
