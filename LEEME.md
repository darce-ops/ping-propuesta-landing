# Web PING SA · cómo pasarla a WordPress con Elementor

1. **Imágenes.** Sube `imagenes/ping-logo.png` y `imagenes/ping-impresora.webp` a *Medios*. Si la URL que te da WordPress no es `/wp-content/uploads/2026/09/...`, busca y reemplaza esa ruta en los 4 archivos.
2. **Páginas.** Crea 4 páginas con estos enlaces permanentes: Inicio (`/`, márcala como portada en *Ajustes > Lectura*), `servicios`, `nosotros` y `contacto`.
3. **Plantilla.** En cada página: *Editar con Elementor* > engranaje de ajustes > Diseño de página: **Elementor Canvas** (así no se duplica la cabecera del tema).
4. **Pegar.** Agrega un contenedor a ancho completo con relleno 0, arrastra un widget **HTML** y pega el archivo correspondiente de `elementor/` completo.
5. **Datos.** Reemplaza teléfono, WhatsApp (`593000000000`), correo, dirección y horario, y revisa los comentarios `REEMPLAZAR`, `CONFIRMAR` y `PROPUESTA` dentro del código.

`boceto-ping.html` es solo para revisar el diseño en el navegador; no se sube a WordPress.
