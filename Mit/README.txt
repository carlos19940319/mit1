📖 MANUAL DE PERSONALIZACIÓN - LA PIZZERÍA

Este proyecto contiene la página web de tu pizzería lista para PC y móviles.

📂 Estructura del proyecto:
- index.html → Página principal con bienvenida.
- entradas.html → Página de entradas.
- pizzas.html → Página de pizzas.
- bebidas.html → Página de bebidas.
- eventos.html → Página de eventos.
- style.css → Archivo de estilos (colores, fuentes, animaciones).
- script.js → Script para navegación y pestañas activas.
- /img/ → Carpeta de imágenes (logo, bienvenida, productos, fondo).

───────────────────────────────
🔧 Cómo personalizar:

1. Cambiar el LOGO:
   - Reemplaza el archivo /img/logo.png por el logo de tu negocio.
   - El logo aparecerá junto al título con brillo animado.

2. Cambiar la IMAGEN DE FONDO:
   - Reemplaza /img/fondo.jpg por tu propia imagen de fondo.
   - También puedes editar en style.css la línea:
     --fondo-img: url("img/fondo.jpg");

3. Cambiar la IMAGEN DE BIENVENIDA:
   - Reemplaza /img/bienvenida.jpg por la foto que quieras mostrar al inicio.

4. Agregar o cambiar PRODUCTOS:
   - Abre entradas.html, pizzas.html o bebidas.html.
   - Cada producto está en un bloque:
     <div class="card">
       <img src="img/pizza1.jpg" alt="Pizza">
       <h3>Pizza Margarita</h3>
       <p>Descripción aquí</p>
       <button>Ordenar</button>
     </div>
   - Duplica este bloque para agregar más productos o cámbialo a tu gusto.

5. Colores del SITIO (paleta vino + dorado + crema):
   - En style.css, al inicio están las variables:
     --color-principal: #800020;  /* Vino */
     --color-secundario: #FFD700; /* Dorado */
     --color-fondo: #fff8f0;      /* Crema */
   - Puedes cambiarlas por otros colores si lo deseas.

6. Animaciones:
   - El título y el logo tienen un brillo dorado animado.
   - La bienvenida tiene texto y una imagen con animación suave.
   - Puedes ajustar la velocidad editando los valores "3s" o "2s" en style.css.

───────────────────────────────
✅ Recomendación:
- Usa imágenes JPG o PNG con buena resolución.
- Mantén nombres de archivos simples (sin espacios).

¡Listo! Tu sitio ya está optimizado para PC y móviles.
