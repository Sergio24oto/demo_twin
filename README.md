# Twin Fest — Demo

Prototipo de compra de entradas con combos, invitaciones, ingreso, entrega en barra y resumen de preventa.

## Coolify

- Repositorio: `Sergio24oto/demo_twin`
- Rama: `main`
- Build Pack: `Dockerfile`
- Directorio base: `/`
- Dockerfile: `/Dockerfile`
- Puerto de la aplicación: `80`
- Asignar el dominio o subdominio de la demo y habilitar HTTPS.
- No requiere variables de entorno, base de datos ni comando de compilación.

Alternativamente se puede servir `index.html` y `assets/` con cualquier servidor estático.

## Uso

Abrir Cliente, elegir un combo y probar Puerta, Barra y Resumen. Lautaro permite crear cortesías. El botón Volver a empezar borra las pruebas del navegador.

Datos y precios de ejemplo. No hay cobros, mensajes enviados, autenticación ni QR real. El estado se guarda en localStorage y no se sincroniza entre dispositivos. Usar nombres ficticios. La imagen de portada es una recreación visual de presentación, no una fotografía documental del establecimiento.

## Archivos

- `index.html`: interfaz, estilos y lógica de la demo.
- `assets/twin-fest-logo.jpg`: logo proporcionado para la presentación.
- `assets/twin-fest-party-branded.png`: portada de la presentación.
- `Dockerfile`: servidor estático Nginx para despliegue.
