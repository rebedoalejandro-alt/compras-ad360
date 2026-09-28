# Compras AD360 por centro

Panel de la compra por albarán de los centros AURGI y MOTORTOWN en AD360.

**Panel:** https://rebedoalejandro-alt.github.io/compras-ad360/

Periodo publicado: 2026-08-01 a 2026-09-28  
Última actualización: 2026-09-28T16:43:34  
Líneas: 8850 - Albaranes: 5872 - Centros: 30

## Datos en bruto

- [`datos/lineas.csv`](datos/lineas.csv): una fila por artículo comprado.
- [`datos/albaranes.csv`](datos/albaranes.csv): una fila por albarán.
- [`datos/datos.json`](datos/datos.json): lo mismo, compacto, que lee el panel.

Los importes `neto` son sin IVA (PVP menos descuento, por unidades). El `total_con_iva` de los albaranes incluye el 21 %. Las devoluciones llevan unidades e importes negativos.

## Centros de los que faltan datos (5)

Los totales de este panel **no incluyen** estos centros:

- **21 LEGANES** (AURGI): no se ha podido leer este centro.
- **22 SAN FERNANDO** (AURGI): no se ha podido leer este centro.
- **85 MAJADAHONDA** (AURGI): AD360 rechaza la contraseña del centro.
- **167 ISLAZUL** (AURGI): no hay usuario para este centro en el fichero de accesos.
- **194 ARROYOMOLINOS** (MOTORTOWN): AD360 rechaza la contraseña del centro.

Se actualiza solo cada día a las 09:00 y a las 15:00. Generado automáticamente: no edites este repositorio a mano, los cambios se sobrescriben.
