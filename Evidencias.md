# 📁 PANEL DE EVIDENCIAS - MI TAQUERÍA

Este documento contiene las pruebas visuales del desarrollo del proyecto final, así como la reflexión sobre el proceso de aprendizaje.

---

## 🌐 Despliegue en Vivo
Puedes ver el sitio web funcionando en tiempo real a través de **GitHub Pages** en el siguiente enlace:

👉 [**Ver Mi Taquería Online**](https://lupis1999.github.io/proyecto-final-a-devf/)

---

## 📸 Capturas de Pantalla (Screenshots)
Aquí se muestran las evidencias del sitio funcionando en local y desplegado:

| Sección | Captura de Pantalla |
| :--- | :--- |
| **Página Principal (Hero)** | ![Inicio](screenshots/inicio.png) |
| **Sección Servicios** | ![Servicios](screenshots/servicios.png) |
| **Sección Contactos** | ![Contacto](screenshots/contacto.png) |
| **Diseño Responsivo** | ![Movil](screenshots/movil.png) |

---

## 💡 APRENDIZAJES

### 1. ¿Qué fue lo más fácil y lo más retador?
*   **Lo más fácil:** Estructurar el HTML semántico, ya que la lógica de las secciones (Inicio, Servicios, Contacto) estaba muy clara desde el boceto inicial.
*   **Lo más retador:** Lograr el efecto **Glassmorphism** (cuadro difuminado) en el menú de navegación. Fue difícil equilibrar la transparencia (`rgba`) con el desenfoque (`backdrop-filter`) para que el texto fuera legible sobre la imagen de fondo.

### 2. ¿Qué etiquetas semánticas usaste y por qué?
Utilicé las siguientes para mejorar el SEO y la accesibilidad:
*   `<header>` y `<nav>`: Para organizar la identidad y la navegación principal.
*   `<section>`: Para dividir el contenido en bloques temáticos (Inicio, Horarios, Servicios).
*   `<article>`: Para la descripción del "Menú Variado", ya que es contenido independiente.
*   `<footer>`: Para contener los derechos reservados y el cierre de la página.

### 3. ¿Cómo organizaste tus commits?
Seguí una estructura de mensajes descriptivos para mantener un historial limpio:
*   `feat:` para nuevas funcionalidades (ej: `feat: agregar formulario de contacto`).
*   `style:` para cambios en el CSS (ej: `style: aplicar efecto glass al nav`).
*   `docs:` para actualizaciones en el README o este archivo de evidencias.

### 4. ¿Qué mejorarías en la siguiente iteración?
Me gustaría implementar un JS para pantallas pequeñas (móviles) usando un poco de JavaScript, y optimizar el peso de las imágenes para que la página cargue aún más rápido en conexiones lentas.

---
**Desarrollado en el bootcamp de Dev.F - 2024**
