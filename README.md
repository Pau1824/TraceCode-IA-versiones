# TraceCode IA – versiones

Aquí se publican, como *releases*, las actualizaciones automáticas de la extensión **TraceCode IA** (UAS – Mochis).

Cada versión incluye únicamente:

- `tracecode-<número>.json.gz`: el paquete de la extensión (código ya compilado y recursos).
- `manifest.json`: número de versión, huella SHA-256 del paquete y notas.
- `manifest.sig`: firma digital (Ed25519) del manifiesto.

La extensión instalada comprueba la firma con una llave pública que ya trae dentro y verifica la huella del paquete antes de usarlo.
Si la firma o la huella no coinciden, descarta la actualización y sigue con la versión que tenía.

Este repositorio **no contiene** datos de alumnos, calificaciones, credenciales ni ninguna llave privada.
No hace falta descargar nada de aquí a mano: TraceCode IA se actualiza solo.
