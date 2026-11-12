# AMD Contable 0.2.0

> uso personal en este Mac; no notarizado por Apple.

- Nuevo módulo **Cripto** para empresas que operan con criptoactivos. Se activa por empresa con **«Opera con criptoactivos»**.
- Importa **reportes UIAF (.txt)** y **Reportes de Operaciones (.xlsx)**. Una vista previa muestra las compras y ventas por mes y qué cambia antes de confirmar. Puedes ver el historial de reportes y revocarlos.
- Cada mes usa **una sola fuente** (UIAF, luego Reporte de Operaciones, luego Bancos) y **nunca se suman entre sí**. Puedes elegir una fuente disponible para un mes; al importar o revocar un reporte, la app vuelve a calcularla según la prioridad.
- Las compras y ventas cripto alimentan los **Estados Financieros** según la integración que configures por empresa y por corte, con presentaciones **OTC, Terceros y DIAN** (con modo predeterminado y alternativo). La configuración y los requisitos de cada corte se gestionan desde Cripto.
- **La facturación electrónica se conserva como ingreso real adicional:** las ventas por factura electrónica siguen entrando a Estados Financieros como hasta ahora, se suman aparte de las cifras cripto y no se promedian, no reciben crecimiento ni dependen de la fuente elegida. Las compras, ventas y movimientos bancarios que no son cripto no cambian.
- Con la integración activa, **«Compra de criptoactivos»** y **«Venta de criptoactivos»** de Bancos dejan de entrar como valores y los reemplaza el módulo Cripto; los saldos y los demás conceptos de Bancos no cambian.
- Los **PDF y las instantáneas históricas** de estados ya generados se conservan sin cambios. Al generar un PDF vigente con la misma base y decisión, los avisos de ese corte quedan resueltos.
- Con el tratamiento **DIAN**, solo el **50 % del GMF** se muestra como gasto y el otro 50 % no deducible se refleja con un ajuste en Patrimonio. La tarjeta de renta explica el cálculo y las autorretenciones de Ventas presentadas.
- Al abrir esta versión, las bases de datos de las empresas se actualizan automáticamente. Conviene tener copia de respaldo.
- Las **facturas de compra y venta de varias páginas** se importan completas. Un archivo cuyo detalle no se pueda reconstruir de forma fiable se rechaza sin guardar datos parciales.
