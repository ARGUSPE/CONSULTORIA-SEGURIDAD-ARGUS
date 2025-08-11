INSTRUCCIONES RÁPIDAS (v4) — Forzar foto en el HERO

1) Sube este archivo al repo y REEMPLAZA: /assets/style.css
2) Asegúrate de tener en /assets/:
   - hero_argus_photo.webp
   - hero_argus_photo.jpg
3) En tu index.html, referencia el CSS con versión para romper caché:
   <link rel="stylesheet" href="assets/style.css?v=4">
4) Guarda (commit) y recarga con Ctrl+Shift+R. En DevTools/Network marca "Disable cache".
