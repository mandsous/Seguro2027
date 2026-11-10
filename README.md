# Seguro 2027 — Open Enrollment

Página para que los clientes de **Manuel De Sousa Ins** dejen sus datos y los de su familia para Open Enrollment 2027.

- En línea: https://mandsous.github.io/Seguro2027/
- Cada envío se guarda en Supabase (proyecto **Seguros**, tabla `solicitudes_oe`) y crea a la persona en el CRM, pestaña "salud".
- La llave que va en la página es pública y **solo permite enviar**: no deja leer, cambiar ni borrar datos.
- Para cambiar la página: editar `index.html`. GitHub Pages la actualiza sola en 1 o 2 minutos.
