# Tras la huella de Joaquín Rodrigo

Gymkhana educativa de Quartell: 7 estaciones, 10 preguntas, 5 audiciones, 7 pistas y diploma final. React 18, TypeScript, Tailwind CSS 3 y Vite.

## Desarrollo
Requiere Node.js 22.
```sh
npm install
npm run dev
npm run build
npm run preview
```

## Netlify
Importar este repositorio desde GitHub, rama main. El archivo netlify.toml configura npm run build, dist, Node 22 y las rutas SPA.

## Códigos QR
Una vez publicado, abrir /qr en el dominio definitivo. Se generan siete QR reales para /parada/1 a /parada/7. Descargar PNG individuales o imprimir todos. Probar con un móvil antes de distribuirlos.

## Uso
Cada equipo utiliza el mismo navegador y dispositivo durante el recorrido. El progreso se almacena localmente, sin cuentas ni servidor. Las estaciones también se pueden abrir manualmente para practicar. Diez puntos por respuesta correcta al primer intento; se permiten reintentos. El enigma se habilita al completar las siete estaciones. El diploma se imprime o guarda en PDF desde el navegador.

## Audiciones y contenido
Las cinco audiciones enlazan a búsquedas de las obras, no a grabaciones verificadas. El docente debe seleccionar previamente fragmentos autorizados y supervisar la escucha. Las preguntas y explicaciones están adaptadas del documento de actividad facilitado. La frase final incluye el inciso que no aparece en los siete fragmentos originales. No se verifica ubicación física ni se centralizan resultados. No introducir nombres completos de menores.

## Comprobación
Ejecutar npm run build y probar inicio, respuestas incorrectas y correctas, recarga, las siete rutas directas, enigma, impresión y QR en un móvil.
