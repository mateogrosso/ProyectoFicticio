# 🪑 E-commerce - Mueblería Hermanos Jota  
# 💻 Grupo 6 - CodeMate  

---

## 👥 Integrantes
- Grosso, Mateo  
- Ferreyra, Tomás Alejo  
- Pereson, Mariano  
- García, Franco  
- Ballardini, Florencia  

---

## 🧠 Descripción del Proyecto
Este proyecto corresponde a la **Fase Final (Sprints 3 y 4)** del e-commerce **Mueblería Hermanos Jota**.  
El objetivo fue reconstruir completamente la tienda digital utilizando tecnologías modernas del lado del cliente y del servidor:  
- **Frontend:** React.js (SPA con componentes reutilizables).  
- **Backend:** Node.js + Express (API REST propia).  

La aplicación ahora funciona como una **Single Page Application (SPA)** conectada a un **servidor Express** que provee los datos en formato JSON.  

---

## ⚙️ Funcionalidades Implementadas
- **Inicio (Home.jsx)**  
  - Hero banner con imagen principal.  
  - Sección de productos destacados obtenidos desde `/api/productos/destacados`.  
  - Contador de carrito sincronizado con `sessionStorage`.  

- **Catálogo (ProductList.jsx)**  
  - Render dinámico de todo el catálogo (`/api/productos`).  
  - Buscador de productos por nombre o descripción.  
  - Botón "Ver detalle" que navega al producto.  

- **Detalle (ProductDetail.jsx)**  
  - Información completa del producto seleccionado.  
  - Botón “Añadir al carrito” con cantidad configurable.  
  - Botón “Volver al catálogo”.  

- **Contacto (ContactForm.jsx)**  
  - Formulario controlado con validación en tiempo real.  
  - Envío al endpoint `/api/contacto`.  
  - Mensajes de error y confirmación en la interfaz.  

- **Carrito (estado global)**  
  - Estado manejado en `App.js`.  
  - Persistencia temporal con `sessionStorage`.  
  - Contador visible en el `Navbar`.  

---

## 🧱 Arquitectura del Proyecto
