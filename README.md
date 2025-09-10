# Ejercicio Práctico: Perfil de Usuario en HTML

Este proyecto es un ejercicio práctico para aplicar conceptos avanzados de **HTML semántico**. Consiste en la creación de una página web que simula un **perfil de usuario**, permitiendo visualizar y editar información personal de manera dinámica.

---

## **Características del Ejercicio**

### **Estructura HTML**
- **Encabezado (`<header>`)**: Contiene el título principal "Perfil de Usuario".
- **Contenido principal (`<main>`)**:
  - **Imagen de perfil**: Muestra la foto del usuario.
  - **Sección de biografía (`<article>`)**: Un párrafo descriptivo sobre el usuario.
  - **Tabla de contacto**: Muestra el email y teléfono del usuario, utilizando `<thead>` y `<tbody>`.
  - **Botón "Cambiar Perfil de Usuario"**: Permite acceder a la sección de edición del perfil.

- **Sección de edición (`<div id="editSection">`)**:
  - **Formulario interactivo**: Permite editar el nombre de usuario, email, teléfono y la sección "Sobre mí".
  - **Botones "Guardar Cambios" y "Cancelar"**: Para confirmar o descartar los cambios realizados.

### **Funcionalidad**
- **Interfaz de usuario intuitiva**: La página principal muestra el perfil y un botón para editarlo.
- **Sección de edición oculta**: Al hacer clic en el botón "Cambiar Perfil de Usuario", se muestra el formulario de edición.
- **Actualización en tiempo real**: Los cambios se reflejan inmediatamente en la página al hacer clic en "Guardar Cambios".
- **Cancelar edición**: Permite ocultar el formulario sin guardar los cambios.

### **Elementos Utilizados**
- Etiquetas semánticas: `<header>`, `<main>`, `<footer>`, `<article>`.
- Tabla estructurada: `<table>`, `<thead>`, `<tbody>`.
- Formulario: Campos `text`, `email`, `tel` y `textarea`.
- Imagen de perfil: Etiqueta `<img>`.
- Meta etiquetas: Para la codificación de caracteres y el viewport.
- JavaScript: Para manejar la interactividad y la actualización de datos.

---

## **Cómo Usarlo**
1. **Abrir el archivo HTML** en cualquier navegador web.
2. **Visualizar el perfil**: La página principal muestra la información del usuario.
3. **Editar el perfil**: Haz clic en el botón **"Cambiar Perfil de Usuario"** para mostrar el formulario de edición.
4. **Modificar los datos**: Completa los campos del formulario con la nueva información.
5. **Guardar los cambios**: Haz clic en **"Guardar Cambios"** para actualizar el perfil.
6. **Cancelar la edición**: Si no deseas guardar los cambios, haz clic en **"Cancelar"**.

---

## **Notas Adicionales**
- Este ejercicio se enfoca en la **semántica y estructura correcta de HTML**, sin depender de estilos CSS.
- El código incluye un script básico en JavaScript para manejar la interactividad del formulario y la actualización de datos.
- Puedes personalizar la imagen de perfil, los textos y los datos de contacto según tus necesidades.
- Si deseas que los cambios persistan después de recargar la página, necesitarás implementar un backend (como PHP, Node.js, etc.).

---

## **Posibles Mejoras Futuras**
- Implementar un backend para guardar los cambios permanentemente.
- Agregar validación de campos en el formulario.
- Permitir la carga de imágenes de perfil desde el dispositivo del usuario.
- Mejorar el diseño visual con CSS.