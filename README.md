# Compras AD360 por centro

Panel de la compra por albarán de los centros AURGI y MOTORTOWN en AD360.

**Panel:** https://rebedoalejandro-alt.github.io/compras-ad360/

Periodo publicado: 2026-08-01 a 2026-09-29  
Última actualización: 2026-09-29T16:26:28  
Líneas: 8877 - Albaranes: 5895 - Centros: 30

## Datos en bruto

- [`datos/lineas.csv`](datos/lineas.csv): una fila por artículo comprado.
- [`datos/albaranes.csv`](datos/albaranes.csv): una fila por albarán.
- [`datos/datos.json`](datos/datos.json): lo mismo, compacto, que lee el panel.

Los importes `neto` son sin IVA (PVP menos descuento, por unidades). El `total_con_iva` de los albaranes incluye el 21 %. Las devoluciones llevan unidades e importes negativos.

## Centros de los que faltan datos (22)

Los totales de este panel **no incluyen** estos centros:

- **21 LEGANES** (AURGI): no se ha podido leer este centro.
- **22 SAN FERNANDO** (AURGI): no se ha podido leer este centro.
- **23 SAN SEBASTIAN** (AURGI): no se ha podido leer este centro.
- **24 PINTO** (AURGI): no se ha podido leer este centro.
- **25 LAS ROZAS** (AURGI): no se ha podido leer este centro.
- **30 PARLA** (AURGI): no se ha podido leer este centro.
- **40 VALLECAS** (AURGI): no se ha podido leer este centro.
- **45 ANTONIO LOPEZ** (AURGI): no se ha podido leer este centro.
- **53 RIVAS** (AURGI): no se ha podido leer este centro.
- **54 VILLALBA** (AURGI): no se ha podido leer este centro.
- **56 ALCALA DE HENARES** (AURGI): no se ha podido leer este centro.
- **57 ALCOBENDAS** (AURGI): no se ha podido leer este centro.
- **58 MOSTOLES** (AURGI): no se ha podido leer este centro.
- **59 VALDEMORO** (AURGI): no se ha podido leer este centro.
- **61 ALCORCON** (AURGI): no se ha podido leer este centro.
- **70 TUCAN** (AURGI): no se ha podido leer este centro.
- **75 EMILIO MUÑOZ** (AURGI): no se ha podido leer este centro.
- **76 AVENIDA DE LOS TOREROS** (AURGI): no se ha podido leer este centro.
- **77 ARGANDA DEL REY** (AURGI): no se ha podido leer este centro.
- **85 MAJADAHONDA** (AURGI): AD360 rechaza la contraseña del centro.
- **167 ISLAZUL** (AURGI): no hay usuario para este centro en el fichero de accesos.
- **194 ARROYOMOLINOS** (MOTORTOWN): AD360 rechaza la contraseña del centro.

Se actualiza solo cada día a las 09:00 y a las 15:00. Generado automáticamente: no edites este repositorio a mano, los cambios se sobrescriben.
