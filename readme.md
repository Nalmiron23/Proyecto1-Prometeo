# Proyecto 1: HTML + CSS

## Requisitos Técnicos y de Contenido

### 1. Estructura y Organización de Archivos

**Archivos:**  
- `index.html`  
- `styles.css`

**Vinculación:**  
El archivo HTML debe incluir la etiqueta `<link>` que vincule correctamente el archivo CSS.

**Estructura HTML básica:**  
Debe incluir:  
- `<!DOCTYPE html>`  
- Etiquetas `<html>`, `<head>` (con metadatos y `<meta name="viewport"...>` para responsividad) y `<body>`  
- Nutrir la etiqueta `<head>` con metadatos como `description`, `author`, `keywords`, etc.

---

### 2. Buenas Prácticas en HTML

**Semántica:**  
Utilizar etiquetas semánticas para estructurar el contenido:  
- `<header>` para la cabecera del sitio  
- `<nav>` para el menú de navegación  
- `<main>` para el contenido principal  
- `<section>` para diferenciar áreas (por ejemplo: "Sobre mí", "Portafolio", "Contacto")  
- `<article>` (opcional) para cada proyecto individual  
- `<footer>` para la parte inferior con información de copyright

**Accesibilidad:**  
Incluir atributos `alt` descriptivos en imágenes y utilizar etiquetas semánticas correctas.

**Validación:**  
El código HTML debe ser válido (se puede comprobar con el [W3C Validator](https://validator.w3.org/)).

---

### 3. Buenas Prácticas en CSS

- **Reset/Normalize:** Incluir un reset o normalize CSS al inicio del archivo.  
- **Variables CSS:** Declarar variables en `:root` para colores, tipografías, etc.  
- **Organización:** Estructurar el código CSS en secciones comentadas (`/* Header */`, `/* Navegación */`, etc.).

---

### 4. Uso de Flexbox y Grid

- **Flexbox:** Usar Flexbox en al menos un contenedor (por ejemplo, para el menú).  
- **Grid:** Usar CSS Grid para mostrar al menos 4 proyectos organizados.

---

### 5. Diseño Responsive

- **Media Queries:** Adaptar el diseño a distintos tamaños de pantalla.  
- **Pruebas:** Verificar funcionamiento en móviles, tablets y escritorio.

---

### 6. Contenido del Sitio

- **Header:** Logotipo o título y navegación.  
- **Sección Hero:** Titular llamativo e imagen o fondo ilustrativo.  
- **Sobre Mí:** Breve información personal o profesional.  
- **Portafolio:** Galería con al menos 4 proyectos (imagen, título, descripción).  
- **Contacto:** Formulario con nombre, email, mensaje y botón de envío.  
- **Footer:** Derechos de autor y enlaces a redes sociales.
