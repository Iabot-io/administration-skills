---
name: invoice-register-reconciliation
description: Extraer y conciliar facturas evitando duplicados y errores de importes o emisor. En IAbot.io, asígnala a un empleado administrativo y aporta facturas, registro contable y criterios de identificación de documentos.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Administración y contabilidad documental
---

# Registro y conciliación de facturas

## Uso en IAbot.io

Asigna esta skill a **un empleado administrativo** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta facturas, registro contable y criterios de identificación de documentos.

**Ejemplo de encargo:** «Contrasta estas facturas con el registro y prepara una lista de duplicados o discrepancias.»

**Resultado a revisar:** Registro estructurado de facturas con conciliación e incidencias.

## Cuándo usarla y qué necesita

Extraer y conciliar facturas evitando duplicados y errores de importes o emisor

Trabaja con facturas, registro contable y criterios de identificación de documentos. Usa documentos y exportaciones contables autorizadas. No presenta declaraciones, contabiliza asientos ni envía correos sin el alcance y permisos correspondientes.

## Procedimiento

1. Identifica emisor, destinatario, serie, número y fecha desde el documento, conservando su archivo.
2. Extrae bases, tipos e importes de impuesto y total sin recalificar fiscalmente la operación.
3. Comprueba sumas, monedas y referencias de rectificación antes de buscar duplicados.
4. Concilia con el registro usando claves combinadas y trata coincidencias parciales como revisión.
5. Entrega datos propuestos y evidencia por campo sin registrar asientos automáticamente.

## Comprobación del resultado

- Una factura rectificativa conserva su relación con la original.
- El total se reconcilia con bases, cuotas y otros conceptos.
- Un mismo número de distintos emisores no se considera duplicado seguro.

## Entrega

Registro estructurado de facturas con conciliación e incidencias.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Agencia Tributaria](https://sede.agenciatributaria.gob.es/)
- [Instituto de Contabilidad y Auditoría de Cuentas](https://www.icac.gob.es/)
