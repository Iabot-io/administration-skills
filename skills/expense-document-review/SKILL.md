---
name: expense-document-review
description: Revisar gastos contra documentación y política sin inferir su deducibilidad fiscal. En IAbot.io, asígnala a un empleado de administración de gastos y aporta justificantes, solicitud de reembolso y política de gastos vigente.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Administración y contabilidad documental
---

# Revisar justificantes de gastos

## Uso en IAbot.io

Asigna esta skill a **un empleado de administración de gastos** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta justificantes, solicitud de reembolso y política de gastos vigente.

**Ejemplo de encargo:** «Revisa estos justificantes y separa los completos de los que necesitan aclaración.»

**Resultado a revisar:** Relación de gastos, evidencias y excepciones a la política.

## Cuándo usarla y qué necesita

Revisar gastos contra documentación y política sin inferir su deducibilidad fiscal

Trabaja con justificantes, solicitud de reembolso y política de gastos vigente. Usa documentos y exportaciones contables autorizadas. No presenta declaraciones, contabiliza asientos ni envía correos sin el alcance y permisos correspondientes.

## Procedimiento

1. Relaciona cada gasto con solicitante autorizado, fecha, motivo y justificante original.
2. Contrasta importes, moneda, duplicados y pagos compartidos entre varias solicitudes.
3. Aplica límites y requisitos de la política vigente indicando el apartado usado.
4. Separa gasto justificado, excepción y dato ausente sin deducir automáticamente el tratamiento tributario.
5. Prepara la revisión para aprobación y conserva el reembolso como acción independiente.

## Comprobación del resultado

- No se reembolsa dos veces un mismo justificante.
- La conversión de moneda tiene fecha y fuente.
- La excepción de política no se presenta como incumplimiento fiscal.

## Entrega

Relación de gastos, evidencias y excepciones a la política.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Agencia Tributaria](https://sede.agenciatributaria.gob.es/)
- [Instituto de Contabilidad y Auditoría de Cuentas](https://www.icac.gob.es/)
