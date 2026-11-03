---
name: bank-statement-reconciliation
description: Relacionar movimientos bancarios y registros internos mostrando coincidencias y diferencias. En IAbot.io, asígnala a un empleado de conciliación administrativa y aporta extractos, registros de cobros y pagos y saldos iniciales.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Administración y contabilidad documental
---

# Conciliar extractos bancarios

## Uso en IAbot.io

Asigna esta skill a **un empleado de conciliación administrativa** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta extractos, registros de cobros y pagos y saldos iniciales.

**Ejemplo de encargo:** «Concilia este extracto y conserva como pendientes las coincidencias ambiguas.»

**Resultado a revisar:** Conciliación de saldos y tabla de movimientos emparejados o pendientes.

## Cuándo usarla y qué necesita

Relacionar movimientos bancarios y registros internos mostrando coincidencias y diferencias

Trabaja con extractos, registros de cobros y pagos y saldos iniciales. Usa documentos y exportaciones contables autorizadas. No presenta declaraciones, contabiliza asientos ni envía correos sin el alcance y permisos correspondientes.

## Procedimiento

1. Fija cuenta, periodo, moneda y saldos; conserva fechas contable y de valor si ambas existen.
2. Normaliza signos y conceptos sin perder la descripción original.
3. Empareja por referencias e importes, tratando pagos agrupados y comisiones con reglas explícitas.
4. Mantén candidatos ambiguos para revisión en lugar de forzar una coincidencia.
5. Reconcilia saldo inicial, movimientos y saldo final y entrega diferencias explicadas.

## Comprobación del resultado

- Ningún movimiento queda emparejado dos veces.
- Los signos de cargos y abonos son consistentes.
- Los movimientos pendientes no se convierten en asientos nuevos por defecto.

## Entrega

Conciliación de saldos y tabla de movimientos emparejados o pendientes.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Agencia Tributaria](https://sede.agenciatributaria.gob.es/)
- [Instituto de Contabilidad y Auditoría de Cuentas](https://www.icac.gob.es/)
