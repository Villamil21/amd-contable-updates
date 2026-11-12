# AMD Contable 0.2.1

> uso personal en este Mac; no notarizado por Apple.

- Las **facturas de compra y venta de varias páginas** se leen completas. Si el detalle no puede reconstruirse con seguridad, el archivo se rechaza sin guardar información parcial.
- Compras reconoce **documentos equivalentes**, incluidos los de peajes, y toma correctamente su **número de documento**.
- Compras reconoce las **líneas cuyo ordinal aparece separado** del resto de su información y conserva las **descripciones partidas** de forma legible.
- Las **declaraciones de IVA con saldo a favor previo y sanción** ahora se importan correctamente: la sanción se registra como gasto y solo genera un pasivo si queda valor por pagar.
- Las **planillas de MiPlanilla** con una página de «Resumen de pago» sin afiliados ahora se leen correctamente: el total esperado se toma del total del resumen y no de un NIT u otro número del documento; si los aportes no cuadran con ese total, la planilla se sigue rechazando.
