# Compras AD360 por centro

Panel de la compra por albaran de los centros AURGI y MOTORTOWN en AD360.

**Panel:** https://rebedoalejandro-alt.github.io/compras-ad360/

Periodo publicado: 2026-08-01 a 2026-09-10  
Ultima actualizacion: 2026-09-10T15:57:52  
Lineas: 7583 - Albaranes: 5044 - Centros: 30

## Datos en bruto

- [`datos/lineas.csv`](datos/lineas.csv): una fila por articulo comprado.
- [`datos/albaranes.csv`](datos/albaranes.csv): una fila por albaran.
- [`datos/datos.json`](datos/datos.json): lo mismo, compacto, que lee el panel.

Los importes `neto` son sin IVA (PVP menos descuento, por unidades). El `total_con_iva` de los albaranes incluye el 21 %. Las devoluciones llevan unidades e importes negativos.

## Centros de los que faltan datos (6)

Los totales de este panel **no incluyen** estos centros:

- **22 SAN FERNANDO** (AURGI): error interno de AD360 al validar el acceso.
- **84 GOYA** (AURGI): AD360 rechaza la contrasena del centro.
- **85 MAJADAHONDA** (AURGI): AD360 rechaza la contrasena del centro.
- **167 ISLAZUL** (AURGI): no hay usuario para este centro en el fichero de accesos.
- **178 PRINCESA** (MOTORTOWN): AD360 rechaza la contrasena del centro.
- **194 ARROYOMOLINOS** (MOTORTOWN): AD360 rechaza la contrasena del centro.

Se actualiza solo cada dia a las 09:00 y a las 15:00. Generado automaticamente: no edites este repositorio a mano, los cambios se sobreescriben.
