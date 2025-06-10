# 🖥️ Proyecto: Sitio Web personalizado con HTML y CSS

## 🧩 Introducción
Con los conocimientos adquiridos en el módulo 3 del Bootcamp, desarrollamos una página de aterrizaje (landing page) que permite al usuario acceder, explorar la interfaz y comprender de qué trata el negocio, junto con los productos y servicios que ofrece.

## 🎯 Propósito
Desarrollar un landing donde el usuario pueda:
- Visualizar el negocio y su identidad gráfica.
- Conocer los servicios disponibles.
- Explorar testimonios reales.
- Suscribirse a novedades.
- Agendar una sesión.

## 📚 Conocimientos aplicados en este proyecto:
1. Construcción de interfaz usando HTML y CSS.
2. Prototipado simple.
3. Uso de etiquetas estándar de HTML5.
4. Creación y vinculación de archivo `index.css` para separar estilos del HTML.
5. Manejo básico de GitHub.
6. Uso de GitHub Pages para publicar y compartir el proyecto.
7. Diseño web responsivo para adaptarse a móviles.

## 📝 Instrucciones generales del desarrollo:
1. Diseño de prototipo simple.
2. Estructura HTML5 para todo el sitio.
3. Aplicación de estilos en CSS.
4. Creación de secciones:
   - Header
   - Main
   - Productos
   - Footer
5. Adaptación responsive opcional para vista móvil.
6. Publicación del proyecto en GitHub:  
   🔗 [Repositorio](https://github.com/KathyVenegas3)

---

## 💼 Desarrollo del proyecto

La landing page está centrada en una tienda online de servicios esotéricos llamada **Gato Místico**. El sitio permite visualizar y simular la reserva de servicios como:

- Lectura de Tarot  
- Lectura de Runas  
- Lectura de Registros Akáshicos  
- Lectura de Carta Astral  

Cada servicio muestra su descripción, duración y valor.

📌 *Prototipo visual: 

![Prototipo](Assets/Prototipado%20landing%20page%20Gato%20M%C3%ADstico_Version%20PNG.png)

## 🔧 Estructura del HTML

El HTML establece la base estructural del sitio. Está compuesto por:

### 1. Header
Contiene:
- Logo del negocio.
- Frase inspiradora.
- Menú de navegación (estático, sin enlaces reales según requerimiento del proyecto).

### 2. Main
Incluye:
- Un formulario para suscribirse a un newsletter.
- Una imagen representativa del mundo esotérico.
- Sección “Sobre mí” con una breve descripción personal.
- Sección “Testimonios” con experiencias de clientes.

### 3. Products
Contiene cuatro tarjetas con imagen, descripción y valor de cada servicio ofrecido. Finaliza con un botón para agendar una sesión.

### 4. Footer
Incluye tres botones:
- **Servicios**: lleva a la sección de productos.
- **Suscribirse**: lleva al formulario.
- **Contáctanos**: lleva al botón de agendamiento.

> 🔗 El HTML se conecta con un archivo CSS externo para mantener una mejor organización y separación de responsabilidades.

---

## 🎨 Explicación técnica de estilos en CSS

El archivo `index.css` fue construido con enfoque modular y responsivo. Se aplicaron las siguientes técnicas:

### 1. 🎨 Variables visuales y tipografía
- Se utilizó la fuente **Caudex** (Google Fonts) por su estilo clásico y místico.
- Colores:
  - Fondo: **negro** (`#000`)
  - Detalles y textos: **dorado suave** (`#d5b154`)

### 2. 📐 Diseño con Flexbox
- Uso extensivo de `display: flex` en secciones clave.
- Aplicación de `flex-wrap`, `gap`, `justify-content` y `align-items` para mantener orden visual adaptable.

### 3. 📱 Diseño responsivo con media queries
- Se aplicó una media query para pantallas menores a **768px**.
- En móviles:
  - El menú hamburguesa reemplaza al menú horizontal.
  - La imagen principal se adapta al ancho total.
  - Las secciones “Sobre mí” y “Testimonios” se reorganizan en vertical.

### 4. ☰ Menú adaptativo
- En escritorio: navegación visible horizontal.
- En móviles: se despliega un menú hamburguesa controlado mediante JavaScript.

### 5. 🔗 Scroll suave
- Uso de `scrollIntoView({ behavior: 'smooth' })` en botones del footer para navegación fluida entre secciones.

### 6. ✨ Estilos personalizados
- Todos los elementos visuales (botones, inputs, tarjetas) fueron estilizados con bordes dorados, fondos oscuros y transiciones para coherencia visual y elegancia.

---

## 🌐 Publicación y acceso
El sitio fue desplegado mediante **GitHub Pages**, lo que permite su visualización desde cualquier dispositivo.

🔗 **URL del sitio:**  
[https://kathyvenegas3.github.io/3.Proyecto_HTML_Landingpage_Modulo_N3/](https://kathyvenegas3.github.io/3.Proyecto_HTML_Landingpage_Modulo_N3/)

