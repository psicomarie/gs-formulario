# Formulario del paciente · Gente Saludable

Página del formulario que el paciente completa desde su celular al escanear el QR de recepción.

- `?tipo=admisional` abre la ficha de ingreso (Admisional).
- `?tipo=anual` abre la ficha anual (Periódico).
- Sin tipo, la página pregunta qué examen viene a hacer.

La página **no guarda datos**. Las respuestas se envían directamente a la planilla privada de Gente Saludable, que está en Google Apps Script.

Está fuera de Google para que funcione aunque el celular del paciente tenga varias cuentas de Google abiertas.

Prototipo en fase de práctica: usar solo con pacientes inventados.

No editar `index.html` a mano: se genera a partir de `Formulario.html` del proyecto de Apps Script.
