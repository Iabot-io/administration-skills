---
name: invoice-coding-proposal
description: Proponer cuentas y dimensiones analíticas con fundamento y revisión para cada factura. En IAbot.io, asígnala a un empleado de apoyo contable y aporta facturas, plan de cuentas y criterios contables de la organización.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Administración y contabilidad documental
---

# Proponer clasificación contable documental

## Uso en IAbot.io

Asigna esta skill a **un empleado de apoyo contable** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta facturas, plan de cuentas y criterios contables de la organización.

**Ejemplo de encargo:** «Propón la clasificación de estas facturas según nuestro plan de cuentas y marca las ambiguas.»

**Resultado a revisar:** Propuesta por documento con cuenta, centro de coste y justificación.

## Cuándo usarla y qué necesita

Proponer cuentas y dimensiones analíticas con fundamento y revisión para cada factura

Trabaja con facturas, plan de cuentas y criterios contables de la organización. Usa documentos y exportaciones contables autorizadas. No presenta declaraciones, contabiliza asientos ni envía correos sin el alcance y permisos correspondientes.

## Procedimiento

1. Lee concepto y documentos asociados sin clasificar solo por el nombre del proveedor.
2. Relaciona la operación con el plan de cuentas y criterios aportados.
3. Separa partidas cuando el documento mezcla conceptos o centros de coste.
4. Marca tratamientos ambiguos, anticipos o periodificaciones que requieren revisión profesional.
5. Entrega una propuesta sin modificar el libro contable ni fijar deducciones fiscales.

## Comprobación del resultado

- Las cuentas propuestas existen en el plan aportado.
- La suma de líneas coincide con la base a distribuir.
- La justificación se refiere al concepto real del documento.

## Entrega

Propuesta por documento con cuenta, centro de coste y justificación.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Agencia Tributaria](https://sede.agenciatributaria.gob.es/)
- [Instituto de Contabilidad y Auditoría de Cuentas](https://www.icac.gob.es/)
