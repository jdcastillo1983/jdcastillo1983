# ImportaCR

Calculadora del precio de venta de cualquier producto importado a Costa Rica por courier aéreo.

**Abrir:** `index.html` funciona sin servidor. Haga doble clic sobre el archivo o publíquelo con GitHub Pages.

## Qué calcula

1. **Valor FOB**: precio del proveedor × cantidad + envío interno e impuesto local.
2. **Flete courier**: peso facturable (el mayor entre peso real y volumétrico, L×A×H÷166 en pulgadas) × tarifa por libra, más cargo fijo y recargo por combustible.
3. **Seguro**: porcentaje sobre FOB + flete (Aduanas aplica uno teórico si no se declara).
4. **Valor CIF** = FOB + flete + seguro.
5. **Impuestos de importación**:
   - DAI (arancel) sobre el CIF.
   - Ley 6946 (1 %) sobre el CIF.
   - Selectivo de consumo sobre CIF + DAI + Ley 6946.
   - IVA (13 %) sobre CIF + DAI + Ley 6946 + Selectivo.
   - Opción de exoneración de pequeño envío familiar (hasta US$ 500 FOB, sin fines comerciales).
   - Opción de tratar el IVA de importación como crédito fiscal.
6. **Trámite aduanal, desalmacenaje y entrega local** (no gravados).
7. **Costo total puesto en Costa Rica** en dólares y colones, por envío y por unidad.
8. **Precio de venta** con margen sobre el precio de venta o markup sobre el costo, IVA de venta y redondeo a ₡100 / ₡500 / ₡1 000 / ₡5 000.

Incluye categorías arancelarias con valores orientativos (electrónica, ropa, calzado, juguetes, cosméticos, suplementos, herramientas, repuestos, libros) y un botón para copiar la cotización como texto.

> Herramienta de estimación. Confirme la partida arancelaria en el Sistema TICA y la tarifa de su courier antes de cotizar en firme.
