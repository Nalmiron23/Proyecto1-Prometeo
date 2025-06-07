Proyecto 1: HTML + CSS


**Requisitos Técnicos y de Contenido**

1. **Estructura y Organización de Archivos**
Archivos:
index.html
styles.css
Vinculación:
El archivo HTML debe incluir la etiqueta <link> que vincule correctamente el archivo CSS.
Estructura HTML básica:
Incluir <!DOCTYPE html>, etiquetas <html>, <head> (con metadatos y etiqueta <meta name="viewport" ...> para responsividad) y <body>.
Nutrir la etiqueta <head>con metadatos suficientes, por ejemplo description, author, keywords, etc…

2. **Buenas Prácticas en HTML**

**Semántica:**  
Utilizar etiquetas semánticas para estructurar el contenido:  
`&lt;header&gt;` para la cabecera del sitio.  
`&lt;nav&gt;` para el menú de navegación.  
`&lt;main&gt;` para el contenido principal.  
`&lt;section&gt;` para diferenciar áreas (por ejemplo: "Sobre mí", "Portafolio", "Contacto").  
`&lt;article&gt;` (opcional) para cada proyecto individual en la sección de portafolio.  
`&lt;footer&gt;` para la parte inferior con información de copyright y redes sociales.

**Accesibilidad:**  
Incluir atributos `alt` descriptivos en imágenes y utilizar etiquetas semánticas correctas.

**Validación:**  
El código HTML debe ser válido (se puede comprobar con el [W3C Validator](https://validator.w3.org/)).


3. **Buenas Prácticas en CSS**
Reset/Normalize:
Incluir un reset o normalize CSS al inicio del archivo para evitar estilos predeterminados inconsistentes.
Variables CSS:
Declarar variables en el selector :root para definir colores, tipografías y otros valores reutilizables.
Organización y Comentarios:
Estructurar el código CSS en secciones comentadas (por ejemplo, "Header", "Navegación", "Sección Portafolio", etc.) para facilitar la legibilidad y mantenimiento.

4. **Uso de Flexbox y Grid**
Flexbox:
Implementar Flexbox en al menos un contenedor. Por ejemplo, se puede utilizar para el menú de navegación o para alinear elementos dentro de una sección.
Grid:
Emplear CSS Grid para la disposición de elementos en la sección de portafolio (por ejemplo, para mostrar una galería de proyectos con al menos 4 elementos distribuidos de forma ordenada).

5. **Diseño Responsive**
Media Queries:
El diseño debe adaptarse a distintos tamaños de pantalla. Utilizar media queries para ajustar la disposición y el tamaño de los elementos (por ejemplo, cambiar la distribución de la galería o el menú en pantallas pequeñas).
Pruebas de Responsividad:
Asegurarse de que el sitio funcione correctamente en dispositivos móviles, tablets y escritorio.

6. **Contenido del Sitio**
Header:
Incluir un logotipo o título representativo y un menú de navegación con enlaces a las secciones principales.
Sección Hero:
Una sección principal (hero) que contenga un titular llamativo y, opcionalmente, una imagen de fondo o ilustración.
Sobre Mí:
Un apartado breve con información personal o profesional.
Portafolio:
Una galería que muestre al menos 4 proyectos. Cada proyecto puede incluir una imagen, título y una breve descripción. Pueden ser inventados si no sabéis que poner.
Contacto:
Un formulario básico con campos para nombre, email y mensaje. Se puede incluir un botón de envío (no es necesario implementar la funcionalidad del formulario, solo el marcado y estilos).
Footer:
Información adicional, como derechos de autor y enlaces a perfiles de redes sociales.
