# AMD Contable 0.2.4

> uso personal en este Mac; no notarizado por Apple.

- Compras reconoce **facturas electrónicas cuya columna de ordinales se imprime antes de los bloques de descripción e importes**: cada fila recupera su descripción y sus cifras en el orden correcto. Si el detalle no se puede reconstruir con exactitud (falta texto de una fila o los totales no cuadran al centavo), el archivo se sigue rechazando completo, sin guardar información parcial.
- En **Nómina › Independientes** se puede **corregir la fecha «Desde» de un concepto de honorarios**, tanto de la versión vigente como de la primera o de una histórica. La corrección exige un **motivo**, mantiene la vigencia **continua** (la versión anterior del concepto cierra sola el día previo) y queda en un **historial** que registra también ese ajuste. Si alguna cuenta de cobro ya registrada cambiaría de vigencia, o la fecha dejaría huecos o solapes, se rechaza sin guardar nada. No modifica cuentas de cobro, documentos ni envíos ya emitidos.
