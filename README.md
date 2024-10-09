# Modelo-entidad-relacion.-Farmacia
### Descripción de cada una de las entidades definidas.
Farmacia: Representa la entidad central de la cual se derivan los medicamentos y sus relaciones con laboratorios y compras.

Medicamento: Cada medicamento tiene los siguientes atributos:
- Código: Un identificador único para cada medicamento.
- Nombre: El nombre comercial o genérico del medicamento.
- Tipo: Puede indicar la clasificación (genérico, de marca, etc.).
- Precio: El costo del medicamento.
- Unidades vendidas: La cantidad total vendida.
- Unidades en stock: La cantidad disponible para la venta.

Laboratorio: Es la entidad que fabrica o provee los medicamentos. Sus atributos son:
- Código: Identificador único para el laboratorio.
- Nombre del laboratorio: Nombre oficial.
- Teléfono: Información de contacto.
- Dirección postal: Ubicación física del laboratorio.
- Fax: Otro medio de contacto.

Compra: Esta entidad almacena los detalles de las compras realizadas por la farmacia, con atributos como:
- Unidades compradas: La cantidad de un medicamento adquirido.
- Fecha de compra: El día en que se realizó la compra.
- Precio total: El valor total de la transacción.

Familias: Agrupa medicamentos en diferentes familias o categorías para su organización.

### Descripción y ejemplos ilustrativos del dominio de cada uno de los atributos de las entidades y de las relaciones.
Ejemplos de dominio de los atributos:
- Código de medicamento: Puede ser una cadena alfanumérica, por ejemplo, "MED1234".
- Precio: Un valor numérico positivo, por ejemplo, 15.50 (en la moneda local).
- Unidades vendidas: Un número entero que representa cuántas unidades se han vendido, como 100.
- Nombre del laboratorio: Una cadena de texto, por ejemplo, "Laboratorios XYZ".
- Fecha de compra: Un atributo de tipo fecha, como "2024-10-09".

### Descripción de cada una de las relaciones definidas. Describa con detalle la cardinalidad de cada relación.
Relación entre Medicamento y Laboratorio:
- Un medicamento es producido por un laboratorio.

Relación de Compra:
- Una compra está relacionada con uno o varios medicamentos.

Relación de Catalogación:
- Los medicamentos se agrupan en diferentes familias.
