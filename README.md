# Crear un Sitio Web Simple con Categorías y un Blog con-Markdown

Hemos creado un sitio web estático con HTML, CSS y JavaScript, que incluye un blog basado en archivos Markdown. El sitio es fácil de mantener y se puede desplegar fácilmente en GitHub Pages.

**¿Por qué es esto útil?**
Este enfoque es ideal para sitios personales o de pequeñas empresas, donde el contenido no cambia constantemente y no se necesita un backend complejo. Además, aprovechar GitHub Pages reduce costos y complejidad, ya que no se necesita gestionar un servidor propio.

### Paso 1: Estructura del Proyecto

**¿Qué estamos haciendo aquí?**
Estamos organizando los archivos y carpetas que componen nuestro sitio web. La estructura de directorios es importante porque determina cómo se acceden y cargan los diferentes recursos (como estilos CSS, scripts JavaScript, y contenido Markdown) en nuestro sitio web.

**¿Por qué es importante?**
Al tener una estructura bien organizada, aseguramos que el sitio web sea fácil de mantener y expandir. Además, GitHub Pages (que usaremos para desplegar el sitio) requiere que nuestros archivos estén organizados de una manera que respete las rutas relativas que usaremos en nuestros enlaces y scripts.

### Paso 2: Configurar la Página Inicial y Categorías

**`index.html` y las páginas de categorías:**

**¿Qué estamos haciendo aquí?**
Estamos creando la página principal del sitio y las páginas para las diferentes categorías. En estas páginas, usamos HTML para estructurar el contenido y CSS para darle estilo. Los enlaces en la página principal (`index.html`) nos permiten navegar a las categorías y al blog.

**¿Por qué es importante?**
Esto define la base de la navegación del sitio web. El `index.html` actúa como la entrada principal de tu sitio, mientras que las páginas de categorías permiten organizar el contenido en secciones, lo que mejora la experiencia del usuario al navegar.

### Paso 3: Configurar la Página del Blog

**`blog.html`:**

**¿Qué estamos haciendo aquí?**
Estamos creando una página dedicada para el blog. Esta página mostrará una lista de entradas del blog, que luego serán renderizadas desde archivos Markdown.

**¿Por qué es importante?**
El blog es una parte central del sitio que presenta contenido dinámico (diferentes publicaciones) de manera estática (HTML). Aquí preparamos el espacio donde esas publicaciones serán mostradas al usuario.

### Paso 4: Crear el JavaScript para Manejar Markdown

**`assets/js/script.js`:**

**¿Qué estamos haciendo aquí?**
Estamos escribiendo un script en JavaScript que lee archivos Markdown, los convierte a HTML, y los inserta en la página del blog. Usamos la biblioteca `marked.js` para convertir Markdown a HTML.

**¿Por qué es importante?**
Markdown es un lenguaje de marcado ligero que permite escribir contenido fácilmente. Sin embargo, los navegadores web entienden HTML, no Markdown. Este script es el puente que traduce Markdown a HTML en tiempo real, permitiendo que los archivos `.md` se muestren correctamente en la web.

### Paso 5: Crear los Archivos Markdown

**`post1.md`, `post2.md`, `post3.md`:**

**¿Qué estamos haciendo aquí?**
Estamos creando archivos Markdown que contienen el contenido de las publicaciones del blog.

**¿Por qué es importante?**
Estos archivos son el contenido real del blog. Escribimos en Markdown porque es más sencillo y limpio que escribir directamente en HTML. Markdown es ampliamente usado por su simplicidad para crear texto formateado.

### Paso 6: Estilos CSS

**`assets/css/styles.css`:**

**¿Qué estamos haciendo aquí?**
Estamos definiendo los estilos visuales de nuestro sitio web. Esto incluye la apariencia del cuerpo de la página, los encabezados, la navegación, y el estilo de las publicaciones del blog.

**¿Por qué es importante?**
CSS se encarga de cómo se verá tu sitio web. Una buena hoja de estilos asegura que el sitio sea atractivo y fácil de usar, mejorando la experiencia del usuario.

### Paso 7: Despliegue en GitHub Pages

**¿Qué estamos haciendo aquí?**
Estamos subiendo nuestro proyecto a GitHub y habilitando GitHub Pages para que nuestro sitio esté disponible en la web.

**¿Por qué es importante?**
GitHub Pages es una forma gratuita y fácil de desplegar sitios web estáticos. Al seguir estos pasos, nuestro sitio web se vuelve accesible en línea, sin necesidad de configurar un servidor.
