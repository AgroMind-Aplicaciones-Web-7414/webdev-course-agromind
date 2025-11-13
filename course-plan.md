# 🌐 Fundamentos de Desarrollo Web

## 📘 Resumen del Curso
Este curso de **1 hora** introduce a estudiantes de secundaria (de 12 a 17 años) en los **fundamentos del desarrollo web**, utilizando **HTML y CSS** de manera práctica y visual.  
El aprendizaje se basa en ejercicios interactivos en línea y explicaciones simples, sin necesidad de instalar software.

**Duración total:** ~60 minutos  
**Público objetivo:** Estudiantes de 12 a 17 años sin experiencia en programación  
**Prerrequisitos:** Ninguno  
**Herramientas necesarias:** Solo un navegador web (Chrome, Firefox, Safari o Edge)

**📂 Repositorio de código fuente:**  
[https://github.com/AgroMind-Aplicaciones-Web-7414/webdev-course-agromind](https://github.com/AgroMind-Aplicaciones-Web-7414/webdev-course-agromind)

---

## 🎬 Secuencia de lecciones

### Lección 1: ¿Qué es el desarrollo web? 

- **Descripción:** En esta lección aprenderás qué es un sitio web, cómo funciona y cuáles son los dos lenguajes fundamentales del desarrollo web: HTML y CSS.
  Descubrirás cómo ambos trabajan juntos para crear páginas estructuradas y con estilo, y al final construirás tu primer esquema visual de una página con encabezado, cuerpo y pie de página. 🚀
- **Enlace:** [Ver la lección](https://youtu.be/ksDx_4th5zI)
- **Consejos clave:** 
  - Piensa en un sitio web como una casa digital: el HTML es su estructura y el CSS su decoración.

  - Aprende paso a paso: primero la estructura, luego el diseño.

  - Experimenta en CodePen; es un entorno ideal para practicar sin instalar nada.

  - La clave es entender la base antes de crear algo complejo.
- **Práctica:** 
  - Crea un esquema básico de un sitio web usando HTML.
    Incluye tres secciones principales:

    - Encabezado con un título o saludo.

    - Cuerpo con un texto breve o una idea principal.

      - Pie de página con información final o contacto.
    
        💡 Puedes usar este código como punto de partida en CodePen:

            - <header>
                <h1>Bienvenidos a mi sitio web</h1>
                    <p>Aquí empieza todo 🚀</p>
                </header>

              <main>
                <h2>Contenido principal</h2>
                    <p>En esta parte va la información más importante, como textos, imágenes o secciones interesantes.</p>
              </main>

              <footer>
                <p>© 2025 Mi sitio web | Contáctanos en redes sociales 📱</p>
              </footer>

### Lección 2: Estructura básica de HTML

- **Descripción:**
En esta lección aprenderás la estructura básica de HTML utilizando el editor en línea CodePen.io. Verás cómo funcionan las etiquetas principales (<html>, <head>, <body>), cómo crear encabezados y párrafos, y cómo construir tu primera página web con título y texto de presentación.
Perfecto para principiantes que quieren iniciarse en el desarrollo web sin instalar ningún programa.
  
- **Enlace:** [Ver la lección](https://www.youtube.com/watch?v=ajL-icFDeRs&t=66s)
- **Consejos clave:**
  
- Cierra siempre tus etiquetas correctamente.

- Mantén el código ordenado e indentado.

- Usa CodePen para probar y ver los cambios en tiempo real.

- Empieza simple: título y párrafos son la base de toda página web.
- 
- **Práctica:**
``` html 

  <body>
      <h1>Mi primera web</h1>
      <p>Bienvenidos a mi primera página web</p>
      <p>Esta es la estructura principal <br> de un documento HTML.</p>
  </body>
````

### Lección 3: Elementos HTML comunes 

- **Descripción:** 

  En esta lección aprenderás a enriquecer tu página web agregando listas, imágenes y enlaces.
  Descubrirás cómo organizar contenido, mostrar fotos y conectar tu sitio con otras páginas, usando los atributos más importantes: src, href y alt.
  Al final, tendrás una pequeña página de hobbies con una lista, una imagen y un enlace funcional. 🎯
- **Enlace:** [Ver la lección](https://youtu.be/LxCKUfD7P30)
- **Consejos clave:** 
  - Usa listas `<ul>`, `<ol>`, `<li>` para organizar información como hobbies, tareas o pasos. 
  - Las imágenes se insertan con `<img>` y deben tener siempre un texto alternativo `(alt)` por accesibilidad.
  - Los enlaces ``(<a>)`` conectan páginas y se abren en una nueva pestaña usando `target="_blank".` 
  - Combina tus nuevos elementos para crear una página más completa y visual.
- **Práctica:**
  - Agrega a tu página una lista de hobbies, una imagen y un enlace dentro del contenido. 
  - Usa este código como punto de partida en JSFiddle o CodePen:

    ```html
    <h1>Mis hoobies</li>

    <ul>
        <li>Leer</li>
        <li>Correr</li>
        <li>escuchar musica</li>
    </ul>

    <img src="https://dus6dayednven.cloudfront.net/app/uploads/2022/05/1-DSC00855-Editar_baja.jpg" alt="foto de un perrito">

    <a href="https://www.google.com/?hl=es&zx=1763045414891&no_sw_cr=1" target="_blank">Ir a google</a>
    ````

  * 💡 Experimenta cambiando el texto, la imagen y el enlace por tus propios intereses.
  * Observa cómo el navegador interpreta cada etiqueta y muestra el resultado.

  - [Editar en JSFiddle](https://jsfiddle.net/z4vqjwu3/) 👈


### Lección 4: Introducción a CSS y primeros estilos

- **Descripción:**

    En esta lección aprenderas como darle estilo a una pagina web usando CSS. Veras como cambiar colores, fuentes, margenes y relleno. Ademas, conoceras las diferentes formas de poder entrenalzar tu archivo HTML con CSS. Al final, tendras una pequeña pagina donde se aplicara todo lo aprendido 🥳
- **Enlace:** [Ver la lección](https://youtu.be/u_7TpxH95qo)
- **Consejos clave:**
  - Organiza siempre tus archivos 
  - Nombra bien tus clases, evita nombres genericos como .azul o .texto1
  - Prueba y juega con los estilos, experimentar es la mejor manera de aprender
  - Cuida el orden del CSS, recuerda que el navegador aplica los estilos en orden: si dos reglas afectan lo mismo, la ultima gana
  - Usa comentarios y revisa errores simples, utiliza /**/ para poder comentar tu codigo y recordar que hace cada seccion
- **Práctica:**
  - Agrega a tu pagina estilos, cambia el tipo de fuente, centra el contenedor y cambia el color de fondo del boton
  - Usa este codigo como punto de partida en JSFiddle o CodePen:

    ```html
    <!DOCTYPE html>
    <html lang="es">
        <head>
            <meta charset="UTF-8">
            <title>Practicando</title>
            <link rel="stylesheet" href="">
        </head>
        <body>
            <div class="tarjeta">
                <h1>Hola mundo</h1>
                <p>Este es un ejemplo sencillo para practicar tus primeros estilos</p>
                <button>Haz click aqui</button>
            </div> 
        </body>
    </html>
    ````

### Lección 5: Proyecto final, mi primera página web

- **Descripción:** En esta lección, aplicarás todo lo aprendido. Combinarás tu estructura HTML completa con contenido enriquecido y estilos CSS para construir tu primera pagina web cohesiva. El objetivo es crear una página de presentación personal o sobre un tema que te guste.
- **Enlace:** [Ver la lección](https://youtu.be/XBRce-Lqudk?si=M1b6zjHbeEjAYNtU)
- **Consejos clave:**
  - Reutiliza tu código: No empieces desde cero. Usa la estructura completa de la Lección 2 como base.
  - Planifica el contenido: Decide el tema (¿Sobre ti? ¿Tu hobby? ¿Tu mascota?).
  - Ve por partes: 1. Estructura HTML. 2. Contenido. 3. Estilos CSS.
  - No temas experimentar: El objetivo es aplicar los conceptos.
- **Práctica:**
  - Crea una página "Sobre Mí" en CodePen o tu editor. Debe cumplir con todos los requisitos de las lecciones anteriores (estructura, elementos, y estilos CSS básicos).

```html
<head>
    <meta charset="UTF-8">
    <title>Mi Primera Página Web</title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff; /* Fondo Azul muy claro */
            color: #333; 
        }
        header {
            background-color: #004a99; 
            color: white;
            text-align: center;
            padding: 20px;
        }
        main {
            padding: 15px;
        }
        img {
            width: 200px;
            border-radius: 8px; 
        }
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9em;
        }
    </style>
</head>

<body>

    <header>
        <h1>Mi Nombre</h1>
        <p>Estudiante de Desarrollo Web 🚀</p>
    </header>

    <main>
        <h2>Sobre Mí</h2>
        <p>¡Hola! Estoy aprendiendo a crear páginas web. Este es mi proyecto final.</p>
        
        <img src="[https://via.placeholder.com/200](https://via.placeholder.com/200)" alt="Una imagen de placeholder">
        
        <h3>Mis Hobbies:</h3>
        <ul>
            <li>Aprender a programar</li>
            <li>Ver series</li>
            <li>Jugar videojuegos</li>
        </ul>
    </main>

    <footer>
        <p>Puedes encontrarme en <a href="[https://www.google.com](https://www.google.com)" target="_blank">Google</a>.</p>
        <p>© 2025 - Creado por Mí</p>
    </footer>

</body>
</html>

```

## 📁 Recursos adicionales

- **Código fuente completo:**
  [https://github.com/AgroMind-Aplicaciones-Web-7414/webdev-course-agromind](https://github.com/AgroMind-Aplicaciones-Web-7414/webdev-course-agromind)


## 👥 Elaboración

**Universidad Peruana de Ciencias Aplicadas (UPC)**  

**Carrera:** Ingeniería de Software  

**Curso:** 1ASI0730 – Aplicaciones Web  

**Ciclo académico:** 202520  

**NRC:** 7414 

**Nombre del equipo:** Agromind

**Líder del equipo:** Anjali Amaro Villar
**Integrantes del equipo:**
- Aaron Santiago Baquerizo Cirilo
- Maria Fernanda Mostajo Orosco
- César Augusto Navarro Correa
- Romina Alejandra Tuesta Marin 

  **Fecha de entrega:** Jueves 13 de noviembre de 2025
