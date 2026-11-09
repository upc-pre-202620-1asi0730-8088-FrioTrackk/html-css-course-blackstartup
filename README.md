
# Mi primera página web con HTML y CSS

Curso de **HTML y CSS** dirigido a estudiantes de secundaria (12–17 años) sin experiencia previa. Organizado en **ocho lecciones de 7 a 8 minutos**, con explicación, demostración y práctica. Construirás una página personal y adaptarás su diseño a distintos tamaños de pantalla.

**Duración** · 60 minutos &nbsp;|&nbsp; **Herramientas** · Navegador web y editor HTML gratuito en línea &nbsp;|&nbsp; **Prerrequisitos** · Ninguno

---

## 📂 Estructura del repositorio

Cuando se suban los materiales, cada rama `leccion-XX` seguirá esta estructura. `XX` corresponde al número de la lección.

```text
html-css-course-blackstartup/
├── starter-files/
│   └── leccion-XX/       # Archivos de inicio para la práctica
├── completed-examples/
│   └── leccion-XX/       # Ejemplo resuelto de la práctica
├── scripts/             # Fragmentos de apoyo para el avatar y las tarjetas
└── README.md
```

**Repositorio completo** · [html-css-course-blackstartup](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup)

`main` contiene la guía general y [`develop`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/develop) es la rama de integración. Las ramas de cada lección están en la tabla.

---

## ▶️ Cómo usar este repositorio

1. Abre [CodePen](https://codepen.io/pen/).
2. Consulta el video de la lección correspondiente cuando se publique su enlace.
3. Abre la rama de la lección. Copia el contenido de `<body>` del archivo inicial en el panel HTML de CodePen. Si la lección incluye `styles.css`, cópialo en el panel CSS.
4. Haz un cambio a la vez y comprueba el resultado en la vista previa.
5. Compara tu página con el ejemplo resuelto en `completed-examples/leccion-XX/`.

**En la lección 3**, también puedes abrir directamente [la práctica de CodePen](https://codepen.io/Sebasti-n-Atauje/pen/JoWxGjr) y usar `scripts/avatar.html` para insertar el avatar. **En la lección 7**, usa `scripts/tarjetas.css` para ajustar las tarjetas al ancho disponible.

**Puedes hacer todas las prácticas desde el navegador.**

---

## 📚 Lecciones

| # | Tema | Duración | Video | Práctica | Responsable |
|---|------|----------|-------|----------|-------------|
| 1 | ¿Qué es un sitio web? | 7 min | Enlace pendiente | [`leccion-01`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-01) | Saavedra Flores, Rodrigo Andree |
| 2 | Tu primer documento HTML | 8 min | Enlace pendiente | [`leccion-02`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-02) | Saavedra Flores, Rodrigo Andree |
| 3 | Listas e imágenes | 7 min | [Ver video](https://www.youtube.com/watch?v=gy5K_zXUArs) | [CodePen](https://codepen.io/Sebasti-n-Atauje/pen/JoWxGjr) · [`leccion-03`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-03) | Atauje Barreto, Alexander Sebastián |
| 4 | Enlaces y secciones | 8 min | Enlace pendiente | [`leccion-04`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-04) | Atauje Barreto, Alexander Sebastián |
| 5 | Colores y fuentes con CSS | 7 min | Enlace pendiente | [`leccion-05`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-05) | Vera Solsol, Nayely Macarena |
| 6 | Centrado, bordes y espacio | 8 min | Enlace pendiente | [`leccion-06`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-06) | Vera Solsol, Nayely Macarena |
| 7 | El perfil en pantallas pequeñas | 8 min | Enlace pendiente | [`leccion-07`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-07) | Daga Chávez, Joaquín Leonardo |
| 8 | Errores comunes y reto final | 7 min | Enlace pendiente | [`leccion-08`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-08) | Daga Chávez, Joaquín Leonardo |

---

### 1️⃣ Lección 1 — ¿Qué es un sitio web?

Distingue el sitio web, sus páginas y el navegador. Usa un título para ver qué parte del ejemplo controla HTML y qué parte controla CSS.

**Contenidos**

- Sitios web, páginas y navegador.
- Texto de un encabezado en HTML y propiedad `color` en CSS.

**Práctica.** Cambia el texto del título y después cambia su color en la vista previa.

**Consejos clave.** Haz un cambio por vez para identificar qué modificó cada panel.

**Piensa y comprueba.** ¿Qué parte del código editarías para cambiar solo el color del título?

---

### 2️⃣ Lección 2 — Tu primer documento HTML

Construye el saludo y la presentación del perfil de Sofía.

**Contenidos**

- Partes de un documento HTML y atributo `lang`.
- Título de la pestaña en `<title>`, encabezado visible en `<h1>` y párrafo en `<p>`.

**Práctica.** Escribe el saludo y añade dos frases de presentación dentro de `<p>`.

**Consejos clave.** En un documento completo, coloca `<title>` en `<head>` y el contenido visible en `<body>`.

**Piensa y comprueba.** ¿Dónde aparece el texto que escribes dentro de `<h1>`?

---

### 3️⃣ Lección 3 — Listas e imágenes

Amplía el perfil con un avatar y una lista de gustos.

**Video de la lección.** [Ver en YouTube](https://www.youtube.com/watch?v=gy5K_zXUArs).

**Código y práctica en línea.** [Abrir en CodePen](https://codepen.io/Sebasti-n-Atauje/pen/JoWxGjr).

**Archivos de la lección.** [`leccion-03`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-03).

**Contenidos**

- Encabezado de sección con `<h2>` y viñetas con `<ul>` y `<li>`.
- Imagen con `<img>`, origen en `src` y texto alternativo en `alt`.

**Práctica.** Agrega el avatar de `scripts/avatar.html` y añade un tercer gusto a la lista.

**Consejos clave.** Escribe cada gusto dentro de su propio `<li>` y revisa que el avatar tenga una descripción.

**Piensa y comprueba.** ¿Qué información aporta `alt` cuando la imagen no carga?

---

### 4️⃣ Lección 4 — Enlaces y secciones

Organiza el contenido del perfil y conecta el saludo con la sección de gustos.

**Contenidos**

- Contenido principal con `<main>` y bloques relacionados con `<section>`.
- Enlace interno con `href="#gustos"` y destino con `id="gustos"`.

**Práctica.** Agrega el enlace «Ver mis gustos» y comprueba que lleve a su sección.

**Consejos clave.** Reduce la altura de la vista previa si toda la página cabe en pantalla y el salto apenas se nota.

**Piensa y comprueba.** ¿Qué ocurre si `href` y `id` escriben «gustos» de manera distinta?

---

### 5️⃣ Lección 5 — Colores y fuentes con CSS

Cambia el fondo, la tipografía y el color del título y del enlace del perfil.

**Contenidos**

- Selector, propiedad y valor de una regla CSS.
- Selectores `body`, `h1` y `a`, y fuente `system-ui`.

**Práctica.** Aplica las reglas una por una y prueba otro color para el título.

**Consejos clave.** Usa `body` para los estilos generales y `h1` para ajustar el título.

**Piensa y comprueba.** ¿Qué regla puedes cambiar para colorear el título sin modificar el fondo?

---

### 6️⃣ Lección 6 — Centrado, bordes y espacio

Convierte el perfil en una tarjeta blanca, centrada y fácil de leer.

**Contenidos**

- Modelo de caja con `padding`, `border` y `margin`.
- Selector `.perfil`, `box-sizing` y centrado con `max-width` y márgenes automáticos.

**Práctica.** Agrega un borde a la tarjeta y prueba `32px` de `padding`.

**Consejos clave.** El `padding` crea espacio dentro del borde. El `margin` lo crea por fuera.

**Piensa y comprueba.** ¿Qué espacio cambia al aumentar el `padding`?

---

### 7️⃣ Lección 7 — El perfil en pantallas pequeñas

Añade «Mi proyecto» y adapta la distribución de las dos tarjetas al ancho disponible.

**Contenidos**

- Contenedor de tarjetas con Flexbox, `flex-wrap` y `gap`.
- Enlace actualizado a `#proyecto` y estilos de `scripts/tarjetas.css`.

**Práctica.** Agrega la sección del proyecto, prueba su enlace y compara la vista amplia con la angosta.

**Consejos clave.** `flex-wrap` permite que una tarjeta pase a otra fila cuando falta espacio.

**Piensa y comprueba.** ¿Qué tarjeta pasa a la fila siguiente al angostar la vista?

---

### 8️⃣ Lección 8 — Errores comunes y reto final

Corrige dos fallos del perfil y comprueba que el resultado funcione en una pantalla pequeña.

**Contenidos**

- Coincidencia entre `href="#proyecto"` e `id="proyecto"`.
- Selector `.tarjetas` y revisión de comillas, cierres de etiquetas y llaves.

**Reto final.** Corrige el destino del enlace y el selector de clase. Luego personaliza un texto o un color y revisa la descripción del avatar, el enlace y la vista angosta.

**Consejos clave.** Corrige un fallo por vez y vuelve a probar después de cada cambio.

**Piensa y comprueba.** ¿Qué cambia en la vista angosta después de recuperar el punto del selector `.tarjetas`?

---

## 🧰 Recursos adicionales

- **Editor en línea** · [CodePen](https://codepen.io/pen/).
- **Archivos de inicio** · `starter-files/`.
- **Ejemplos terminados** · `completed-examples/`.
- **Material de apoyo** · `scripts/`.

**¡Gracias por completar el curso!**

---

## 👥 Equipo

**Institución** · Universidad Peruana de Ciencias Aplicadas (UPC)

**Curso universitario** · Aplicaciones Web

**Equipo** · BlackStartup

| Integrante |
|---|
| Atauje Barreto, Alexander Sebastián |
| Daga Chávez, Joaquín Leonardo |
| Saavedra Flores, Rodrigo Andree |
| Vera Solsol, Nayely Macarena |
