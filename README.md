# Mi primera página web con HTML y CSS

Curso de **HTML y CSS** dirigido a estudiantes de secundaria (12–17 años) sin experiencia previa. Organizado en **cuatro lecciones de 15 minutos**, con 5 minutos de explicación y 10 minutos de demostración y práctica por lección. Construirás una página personal y adaptarás su diseño a distintos tamaños de pantalla.

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
├── scripts/             # Material de apoyo, como el avatar de la lección 2
└── README.md
```

**Repositorio completo** · [html-css-course-blackstartup](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup)

`main` contiene la guía general y [`develop`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/develop) es la rama de integración. Las ramas de cada lección están en la tabla.

---

## ▶️ Cómo usar este repositorio

1. Abre [OneCompiler para HTML](https://onecompiler.com/html).
2. Consulta el video de la lección correspondiente cuando se publique su enlace.
3. Abre la rama de la lección y copia `starter-files/leccion-XX/index.html` en la pestaña `index.html` del editor. Si la lección incluye `styles.css`, cópialo en su pestaña. Deja `scripts.js` vacío.
4. Pulsa **Run** para ver la página. Haz un cambio a la vez y vuelve a ejecutar para comprobar el resultado.
5. Compara tu página con el ejemplo resuelto en `completed-examples/leccion-XX/`.

**En la lección 2**, copia el fragmento completo de `scripts/avatar.html` para que se vea la imagen del ejemplo.

**Puedes hacer todas las prácticas desde el navegador.**

---

## 📚 Lecciones

| # | Tema | Duración | Video | Práctica | Responsable |
|---|------|----------|-------|----------|-------------|
| 1 | Tu primera página web | 15 min | Enlace pendiente | [`leccion-01`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-01) | Saavedra Flores, Rodrigo Andree |
| 2 | Más contenido para tu página | 15 min | Enlace pendiente | [`leccion-02`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-02) | Atauje Barreto, Alexander Sebastián |
| 3 | El primer estilo de tu página | 15 min | Enlace pendiente | [`leccion-03`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-03) | Vera Solsol, Nayely Macarena |
| 4 | Una página que cabe en el celular | 15 min | Enlace pendiente | [`leccion-04`](https://github.com/upc-pre-202620-1asi0730-8088-FrioTrackk/html-css-course-blackstartup/tree/leccion-04) | Daga Chávez, Joaquín Leonardo |

---

### 1️⃣ Lección 1 — Tu primera página web

Crea el perfil de Sofía con un título y un párrafo. Distingue los datos del documento que van en `<head>` del contenido visible que va en `<body>`.

**Contenidos**

- Usa `<title>` para nombrar el documento y `<h1>` para mostrar el encabezado de la página.
- Escribe la presentación dentro de `<p>` y revisa el cierre de las etiquetas.

**Práctica.** Cambia el saludo por un apodo inventado y escribe algo que te guste en el párrafo.

**Consejos clave.** Coloca `<h1>` y `<p>` dentro de `<body>` y comprueba que ambas etiquetas se cierren.

**Piensa y comprueba.** ¿Qué cambia en la pestaña al editar `<title>`? ¿Qué cambia dentro de la página al editar `<h1>`?

---

### 2️⃣ Lección 2 — Más contenido para tu página

Amplía el perfil con un avatar, una lista de gustos y un enlace que lleva a esa sección.

**Contenidos**

- Usa `<img>` con `src` y un texto alternativo en `alt`. El fragmento del avatar se prepara en `scripts/avatar.html`.
- Organiza los gustos con `<section>`, `<h2>`, `<ul>` y `<li>`.
- Conecta el enlace `href="#gustos"` con el destino `id="gustos"`.

**Práctica.** Añade un tercer gusto dentro de `<ul>` y comprueba que aparezca con viñeta.

**Consejos clave.** El texto que sigue a `#` en `href` debe coincidir con el `id` de la sección.

**Piensa y comprueba.** ¿Adónde lleva el enlace «Ver mis gustos» después de agregar la tercera viñeta?

---

### 3️⃣ Lección 3 — El primer estilo de tu página

Conecta `index.html` con `styles.css` y convierte el perfil en una tarjeta blanca sobre un fondo lavanda.

**Contenidos**

- Identifica el selector, la propiedad y el valor en una regla CSS.
- Usa los selectores de etiqueta `body`, `h1` y `a` para cambiar la fuente y los colores. Mantén el enlace subrayado.
- Aplica fondo, espacio interior y esquinas redondeadas a la clase `.perfil`.

**Práctica.** Cambia el `padding` de la tarjeta de `24px` a `32px` y vuelve a ejecutar la página.

**Consejos clave.** Comprueba que `<link>` apunte a `styles.css` y que el selector `.perfil` lleve punto.

**Piensa y comprueba.** ¿Dónde se nota el cambio al aumentar el `padding`?

---

### 4️⃣ Lección 4 — Una página que cabe en el celular

Completa el perfil con una tarjeta de proyecto y adapta la distribución al ancho de la pantalla.

**Contenidos**

- Centra el perfil con `max-width` y márgenes automáticos.
- Agrupa «Mis gustos» y «Mi proyecto» en `.tarjetas`. Usa Flexbox, `flex-wrap` y `gap` para acomodarlas según el espacio disponible.
- Actualiza el enlace para que apunte a `#proyecto`.

**Proyecto final.** Agrega la tarjeta «Mi proyecto» y prueba el enlace en una vista amplia y otra angosta.

**Desafío final.** Escribe tu propia idea de proyecto y comprueba que el texto se lea bien en ambas vistas.

**Consejos clave.** `flex-wrap` permite que una tarjeta pase a la siguiente fila cuando el espacio disponible se reduce.

**Piensa y comprueba.** ¿Qué tarjeta baja cuando angostas la vista previa?

---

## 🧰 Recursos adicionales

- **Editor en línea** · [OneCompiler para HTML](https://onecompiler.com/html).
- **Archivos de inicio** · `starter-files/`.
- **Ejemplos terminados** · `completed-examples/`.
- **Material de apoyo** · `scripts/`.

**¡Gracias por completar el curso!**

---

## 👥 Equipo

**Institución** · Universidad Peruana de Ciencias Aplicadas (UPC)

**Curso universitario** · Desarrollo de Aplicaciones Open Source

**Equipo** · BlackStartup

| Integrante |
|---|
| Atauje Barreto, Alexander Sebastián |
| Daga Chávez, Joaquín Leonardo |
| Saavedra Flores, Rodrigo Andree |
| Vera Solsol, Nayely Macarena |
