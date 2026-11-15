# Puente Clínico

Aplicación web para conectar pacientes y médicos en Chile:

- Elegir región, ciudad y centro de salud.
- Ver médicos disponibles por especialidad, con su horario y próxima hora libre.
- Pedir, confirmar y cancelar horas, con aviso automático a la otra parte.
- Solicitar renovación de recetas.
- Consultas por mensaje entre paciente y médico.
- Avisar incidentes (reacciones a medicamentos, síntomas, atrasos) con nivel de gravedad.
- Panel del médico: agenda, disponibilidad y avisos a sus pacientes.

## Cómo funciona esta versión

Es un solo archivo (`index.html`), sin servidor. Los datos se guardan en el navegador de cada persona (`localStorage`). Por eso:

- Lo que registra un paciente **no lo ve un médico en otro computador**.
- Los médicos y centros incluidos son **de ejemplo** (los nombres de los médicos son ficticios).

Para que pacientes y médicos compartan datos de verdad, hay que conectarla a una base de datos (por ejemplo Firebase o Supabase) y agregar inicio de sesión.

## Aviso

Prototipo de demostración. No ingreses datos de salud reales. En una emergencia llama al **131 (SAMU)**.

## Publicar en GitHub Pages

1. Sube `index.html` y este `README.md` a un repositorio.
2. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
