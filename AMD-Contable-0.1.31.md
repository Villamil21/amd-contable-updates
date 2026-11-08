# AMD Contable 0.1.31

> uso personal en este Mac; no notarizado por Apple.

- En **Compras**, cada factura muestra sus **impuestos discriminados** (IVA, ICUI, INC y otros) y los concilia con los totales del documento y con el QR. Si no coinciden, la factura queda en revisión hasta que confirmes los valores leídos; esa confirmación queda anotada en el historial.
- La **retención** ya no se asume. Si el PDF no la trae, decides por factura entre usar el cálculo o dejarla en cero, y la factura no queda lista hasta que decidas. Si el PDF trae retención explícita en cero, se aplica automáticamente el cálculo. Si trae un valor distinto del cálculo, eliges cuál conservar: el del PDF o el calculado.
- **Sugerencias de clasificación** para PUC, IVA y retención, basadas en coincidencias seguras del mismo proveedor, tipo documental y concepto. Solo llenan campos vacíos, se revisan una por una o con «Copiar todas», y siempre puedes ver por qué se propuso cada una. Una retención sugerida se muestra solo para revisar: no se copia sola.
- Al cambiar una configuración, las sugerencias de las facturas pendientes compatibles se **recalculan**; las facturas enviadas no cambian.
- **Reglas compartidas, solo si tú lo decides.** Desde una factura puedes compartir la cuenta de un concepto con tus otras empresas, reemplazarla o eliminarla. Cada cambio pide confirmación, no expone datos de otras empresas y no modifica líneas ya clasificadas ni facturas enviadas.
- **Propinas, descuentos y recargos globales** tienen sus propias sugerencias de cuenta PUC, independientes de las líneas de producto. Solo proponen la cuenta —nunca IVA ni retención— y se copian de una en una.
- Mejoras de interfaz en Compras:
  - La tabla de productos reparte su ancho según el espacio real de la ventana y abrevia valores largos con «…» en una sola línea.
  - El panel de sugerencias y las pestañas caben en el ancho mínimo de 1280 pt, sin que nada se salga de la ventana.
  - Con la ventana a su altura mínima, la pestaña Impuestos se desplaza y «Confirmar valores leídos» y la última fila siguen alcanzables.
  - El subtítulo de la factura admite dos líneas.
