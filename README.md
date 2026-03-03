🍎 El Palacio de la Fruta - Tienda Online 🛒

Bienvenidos al repositorio oficial de El Palacio de la Fruta, una aplicación web ultrarrápida (Single Page Application) diseñada específicamente para la gestión de productos y recepción de pedidos vía WhatsApp de una verdulería local.

✨ Características Principales

📱 Mobile-First: Interfaz diseñada como una app nativa, con botones grandes, navegación fluida y sin barras de scroll molestas.

🛒 Carrito Dinámico: Cálculo automático de precios por kilo o por unidad, sumando el total en tiempo real.

💬 Integración con WhatsApp: Los pedidos se formatean automáticamente en un mensaje claro, detallado y listo para enviar al número del local.

📍 Geolocalización: Los clientes pueden adjuntar su ubicación GPS exacta con un solo toque para facilitar el delivery.

⚡ Caché Inteligente (Ultra-Rápida): Uso de localStorage para cargar el catálogo al instante (0.001s), sincronizando actualizaciones de fondo.

🔐 Panel de Administración Oculto: Sistema de gestión "Modo Dueño" integrado en la misma vista, protegido por Firebase Auth.

🛠️ Stack Tecnológico

La aplicación está construida sin frameworks pesados para garantizar la máxima velocidad de carga en cualquier dispositivo móvil:

Frontend: HTML5 semántico, Vanilla JavaScript (ES6+).

Estilos: Tailwind CSS (vía CDN) y FontAwesome para la iconografía.

Backend & Base de Datos: Firebase Firestore (Reglas de seguridad estrictas + inicio de sesión anónimo para lectura pública).

Autenticación: Firebase Authentication (Email/Password para el administrador).

Hosting: GitHub Pages.

🔒 Modo Dueño (Admin Panel)

Para mantener la aplicación en un solo archivo (index.html), el panel de control está oculto a la vista del público.
Para acceder:

Hacer triple tap / clic rápido sobre el título "El Palacio de la Fruta" en el encabezado.

Ingresar las credenciales de administrador.

Desde allí se pueden agregar, editar, eliminar precios y cambiar los emojis (🥑, 🥩, 🧊) de todo el catálogo en tiempo real.

🚀 Instalación y Despliegue

Al ser un proyecto Serverless y basado en CDN, no requiere instalación de dependencias locales (Node.js/NPM).

Clonar este repositorio:

git clone [https://github.com/Ruletita/el-palacio-de-la-fruta.git](https://github.com/Ruletita/el-palacio-de-la-fruta.git)


Abrir el archivo index.html en cualquier navegador web moderno.

Para producción: Simplemente subir los archivos a la rama main y activar GitHub Pages.

📞 Contacto y Local

📍 Ubicación: Pres. Hipólito Yrigoyen 2124, Florida, Buenos Aires.

🕒 Horarios: Lunes a Sábados de 07:00 a 20:30 hs.

👨‍💻 Desarrollador: Agus (Ruletita)

Hecho con ❤️ y mucho código para digitalizar el comercio local.
