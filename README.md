# Campo · Plantas

App web para tomar datos de plantas en parcelas desde el móvil o el iPad.

- Ficha de parcela: nombre, ecosistema, fecha, quién toma los datos, elevación, pendiente y orientación.
- Buscador con las especies de Tenerife (`especies.js`, a partir de la lista de campo): por abreviatura (Cyt sup), nombre científico, nombre común o sinónimo. Salen primero las del piso de vegetación de la parcela; las de otros pisos aparecen detrás marcadas como «otro piso». Se pueden añadir especies nuevas desde el propio buscador.
- Botones con las 5 especies más repetidas en la parcela para elegirlas de un toque.
- Obligatorio por planta: especie, altura y dos diámetros perpendiculares (cm).
- Opcional: multiplicador de plantas parecidas (vacío = 1), daño por conejo y por muflón (0–5; vacío = "no observado") y % seco (vacío = en blanco; 100 % = muerta).
- Exportación a CSV (separado por punto y coma, se abre directamente en Excel) con el nombre científico completo.

Los datos se guardan solo en el propio dispositivo y funciona sin cobertura. Desde la pantalla de inicio se puede guardar y cargar una copia de seguridad.

Uso: abrir la web de GitHub Pages en Safari → Compartir → Añadir a pantalla de inicio.
