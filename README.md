El objetivo del proyecto es reforzar habilidades en HTML5:  
- Estructura general de una página web.  
- Uso correcto de etiquetas semánticas.  
- Manejo de formularios.  
- Tablas, listas, enlaces e imágenes.  
- Integración de contenido multimedia (audio y video).  
- Uso de etiquetas poco comunes como `<base>`, `<abbr>` y `<time>`.

---

##  Investigación de etiquetas HTML usadas

### **1. Estructura**
| Etiqueta | Uso |
|---------|-----|
| `html` | Define el documento HTML. |
| `head` | Contiene metadatos y recursos de configuración. |
| `body` | Contiene el contenido visible de la página. |
| `meta` | Especifica metadatos como codificación. |
| `title` | Título mostrado en la pestaña del navegador. |
| `base` | Define la URL base para enlaces relativos. |

### **2. Etiquetas semánticas**
| Etiqueta | Uso |
|---------|-----|
| `header` | Encabezado del sitio o sección. |
| `nav` | Menú de navegación. |
| `main` | Contenido principal del documento. |
| `section` | Agrupación temática de contenido. |
| `article` | Contenido independiente (ej. una tarea). |
| `aside` | Información adicional o complementaria. |
| `footer` | Pie de página del documento. |
| `address` | Información de contacto. |
| `time` | Representa una fecha u hora. |

### **3. Etiquetas no semánticas**
| Etiqueta | Uso |
|---------|-----|
| `div` | Contenedor genérico para agrupar elementos. |
| `span` | Contenedor en línea para resaltar texto. |

### **4. Texto y formato**
| Etiqueta | Uso |
|---------|-----|
| `h1`, `h2`, `h3` | Encabezados jerárquicos. |
| `p` | Párrafos de texto. |
| `strong`, `b` | Texto en negrita o énfasis fuerte. |
| `em`, `i` | Enfasis o estilo en cursiva. |
| `u` | Subrayado. |
| `mark` | Texto resaltado. |
| `abbr` | Abreviaturas con descripción emergente. |

### **5. Listas**
| Etiqueta | Uso |
|---------|-----|
| `ul` | Lista desordenada. |
| `ol` | Lista ordenada. |
| `li` | Elemento de lista. |

### **6. Tablas**
| Etiqueta | Uso |
|---------|-----|
| `table` | Tabla general. |
| `tr` | Fila. |
| `th` | Encabezado de columna. |
| `td` | Celda de datos. |

### **7. Formularios**
| Etiqueta | Uso |
|---------|-----|
| `form` | Define un formulario. |
| `label` | Etiqueta asociada a un campo. |
| `input` | Campo de entrada (texto, número, fecha, etc.). |
| `textarea` | Área de texto extendido. |
| `button` | Botón de acción. |

### **8. Multimedia**
| Etiqueta | Uso |
|---------|-----|
| `img` | Imagen con atributos `src`, `alt`, `width`. |
| `audio` | Reproductor de audio. |
| `video` | Reproductor de video. |
| `source` | Fuente de audio/video con tipo declarado. |

---

## Diferencias entre etiquetas semánticas y no semánticas

### Etiquetas semánticas
Son etiquetas cuyo nombre describe su propósito.  
**Ejemplo:**  
- `<header>`: Encabezado  
- `<nav>`: Navegación  
- `<article>`: Contenido independiente  

**Beneficios:**  
- Mejoran la accesibilidad  
- Ayudan al SEO  
- Hacen el código más legible y organizado  

### Etiquetas no semánticas
No describen su función por sí mismas.  
**Ejemplos:**  
- `<div>` (bloque genérico)  
- `<span>` (estilo en línea)  

**Se usan cuando no existe una etiqueta semántica adecuada**, por ejemplo para aplicar CSS o agrupar elementos.

---

## Enfoque en etiquetas poco comunes

### `<base>`
Define la URL base para todos los enlaces relativos de la página.  
Si el `<base>` es:
<base href="https://ejemplo.com/">
Entonces: <a href="archivo.html">
apunta a: https://ejemplo.com/archivo.html
  
<abbr>:
Permite mostrar el significado de una abreviatura.
<abbr title="Create, Read, Update, Delete">CRUD</abbr>
Al pasar el cursor, se muestra el significado completo.

<time>:
Representa una fecha u hora, útil para máquinas, buscadores y accesibilidad.
<time datetime="2024-02-10">10 de febrero de 2024</time>

Multimedia (audio, video)
Ventajas:
Se reproducen dentro de la página (no requieren aplicaciones externas).
Permiten controles nativos (play, pausa, volumen).
Soportan varias fuentes por compatibilidad.
Mejoran la experiencia del usuario.

Referencias:
MDN Web Docs – https://developer.mozilla.org/
W3Schools – https://www.w3schools.com/
HTML Living Standard – https://html.spec.whatwg.org/
Apuntes de clase y material docente.
