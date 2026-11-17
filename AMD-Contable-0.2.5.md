# AMD Contable 0.2.5

> uso personal en este Mac; no notarizado por Apple.

- **Rediseño de Empresas.** Se renueva el **directorio de empresas**, el **asistente de «Nueva empresa»** (documentos, conciliación, ubicación, socios y capital, y revisión) y **toda la ficha de la empresa**, con una presentación más ordenada y clara. No cambia la información guardada de ninguna empresa.
- **Socios, representantes y personas.** «Socios y representantes» se simplifica; el diálogo **Agregar socio** y la **ficha de la persona** se rediseñan. Si la persona ya está en la ficha, se avisa y se agrega sin crear un duplicado.
- **Más claridad en otras pestañas.** Las **cuentas de ventas**, las **notas financieras** y los **documentos** de la empresa se presentan de forma más sencilla, sin cambiar la lógica de las notas ni de los documentos.
- **Municipios entre RUT y Cámara.** La conciliación reconoce como equivalentes las distintas formas de escribir un mismo municipio, de modo que ya no aparece un conflicto cuando ambos documentos indican el mismo lugar.
- **NIT de Cámara unido a su dígito de verificación.** Si el certificado de Cámara trae el NIT pegado a su DV, se acepta únicamente cuando coincide y valida frente al RUT; en cualquier otro caso se mantiene el conflicto para revisión.
- **Duración indefinida.** Cuando el RUT usa una fecha muy lejana (por ejemplo, 2999‑12‑31) para indicar duración indefinida, se lee como «indefinida» y deja de marcarse como conflicto con la Cámara. Los borradores y las fichas anteriores se corrigen al volver a conciliar, sin tocar decisiones manuales; una fecha real, como 2045‑12‑31, sigue siendo una fecha y mantiene el conflicto.
