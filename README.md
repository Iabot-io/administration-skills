# Administración y contabilidad documental · Skills para empleados IA de IAbot.io

Facturas, gastos, conciliaciones, cierres y correo de trabajo con evidencias y revisiones.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Registro y conciliación de facturas](skills/invoice-register-reconciliation/SKILL.md) | un empleado administrativo | Registro estructurado de facturas con conciliación e incidencias. |
| [Revisar justificantes de gastos](skills/expense-document-review/SKILL.md) | un empleado de administración de gastos | Relación de gastos, evidencias y excepciones a la política. |
| [Proponer clasificación contable documental](skills/invoice-coding-proposal/SKILL.md) | un empleado de apoyo contable | Propuesta por documento con cuenta, centro de coste y justificación. |
| [Conciliar extractos bancarios](skills/bank-statement-reconciliation/SKILL.md) | un empleado de conciliación administrativa | Conciliación de saldos y tabla de movimientos emparejados o pendientes. |
| [Preparar el cierre mensual](skills/month-end-close-checklist/SKILL.md) | un empleado de coordinación del cierre | Lista de cierre con dependencias, responsables y evidencias de finalización. |
| [Convertir correo en acciones de trabajo](skills/inbox-action-register/SKILL.md) | un empleado de gestión administrativa | Registro de acciones y borradores con referencia al mensaje de origen. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/administration-skills --list
npx skills add Iabot-io/administration-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Registro y conciliación de facturas:** «Contrasta estas facturas con el registro y prepara una lista de duplicados o discrepancias.»
- **Revisar justificantes de gastos:** «Revisa estos justificantes y separa los completos de los que necesitan aclaración.»
- **Proponer clasificación contable documental:** «Propón la clasificación de estas facturas según nuestro plan de cuentas y marca las ambiguas.»

## Herramientas y límites

Usa documentos y exportaciones contables autorizadas. No presenta declaraciones, contabiliza asientos ni envía correos sin el alcance y permisos correspondientes.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Agencia Tributaria](https://sede.agenciatributaria.gob.es/)
- [Instituto de Contabilidad y Auditoría de Cuentas](https://www.icac.gob.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
