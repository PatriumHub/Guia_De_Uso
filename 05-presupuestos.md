# 5. Presupuestos

Menú **Presupuestos**.

Sirve para los **gastos fijos / costos del mes** (alquiler, luz, internet, etc.).

## Conceptos

| Concepto | Significado |
|----------|-------------|
| **Gasto** (antes “plantilla”) | Se repite cada mes |
| **Ítem del mes** | La cuota de este período (pendiente / pagado / omitido) |
| **Presupuestos por grupos** | Todos los gastos activos, por persona o empresa |

Los **pendientes** del **mes actual y de meses atrasados** aparecen también en **Pasivos** (total por entidad).  
Si entrás a un mes **adelantado** (ej. septiembre estando en agosto), se generan los ítems para planificar, pero **no suman a pasivos** hasta que el calendario llegue a ese mes.

## Crear un gasto

1. Presupuestos → **Presupuestos por grupos** → **+ Gasto**. Los gastos se crean siempre acá: son recurrentes, no pertenecen a un mes.
2. Entidad, nombre, monto (puede ser 0), día de vencimiento, **categoría** (opc., las mismas de Movimientos), cuenta sugerida.
3. Se genera el ítem del mes actual.

## Mes actual (pantalla principal)

- Filtrá por período y entidad.
- Ves pendientes, pagados y omitidos.
- Columnas ordenables (clic en el encabezado).

### Acciones por fila

En la tabla las acciones son **iconos** (pasa el mouse para ver el nombre).

| Estado | Qué podés hacer |
|--------|------------------|
| **Pendiente** | **Pagar** (amarillo), Omitir, Eliminar (rojo) |
| **Pagado** | Revertir, Eliminar (rojo) |
| **Omitido** | Eliminar (rojo) |

- **Pagar**: elegís cuenta e importe → crea un **egreso** (con la categoría del gasto, si tiene) y deja de contar como pasivo.  
  Si el monto es 0, cierra sin movimiento.  
  Si pagaste un importe distinto al planificado, la fila muestra **lo pagado** y debajo el plan original.
- **Omitir**: deja de contar como pasivo (no pagaste).
- **Revertir**: deshace el pago (anula el egreso y vuelve a pendiente).
- **Eliminar**: saca el ítem del mes y **desactiva** el gasto para que no se regenere (útil para algo de una sola vez).

## Presupuestos por grupos

Lista por entidad con totales.  
En cada grupo ves la tabla (ordená con clic en los títulos), **Eliminar grupo**, y dos gráficos: **composición** y **ranking** (mayor a menor %).  
Al cambiar **tema claro/oscuro**, los gráficos se actualizan solos (no hace falta recargar).  
Ahí podés **editar** o **eliminar** un gasto del grupo (deja de regenerarse; los pagos ya hechos se mantienen).

Al **editar** un gasto, el cambio (monto, nombre, moneda, día de vencimiento, categoría) se aplica a los **ítems pendientes del mes actual y de los meses futuros**. Los ya **pagados** u **omitidos** quedan como estaban, y los **pendientes atrasados** también: son la deuda tal como se facturó.

Es lo que corresponde con la inflación: subís el precio en Presupuestos por grupos y rige de acá en adelante, sin reescribir lo que ya liquidaste.

El total del grupo se muestra **por moneda**: si una entidad tiene gastos en ARS y en USD, vas a ver un total de cada una (no se suman entre sí).

## ¿El total del mes tiene que coincidir con Presupuestos por grupos?

**Sí, mientras el mes esté todo pendiente.** Al abrir Presupuestos, los ítems **pendientes** del mes actual y de meses futuros se reacomodan solos al monto del gasto. Así, filtrando por una persona, el total del mes es igual al total de esa persona en Presupuestos por grupos.

**Deja de coincidir a medida que liquidás el mes**, y eso es correcto:

- **Pagaste por otro importe**: el mes cuenta lo realmente pagado (la fila lo muestra, con el plan debajo).
- **Cerraste un gasto en 0**: suma 0 al mes, pero sigue valiendo su monto en Presupuestos por grupos.
- **Eliminaste un gasto que ya estaba pagado**: el ítem pagado sigue en el mes, pero el gasto ya no está activo.
- **Gastos en otra moneda**: los totales del mes son de la moneda elegida en el filtro.

Los **meses ya pasados no se tocan**: un pendiente atrasado queda con el importe con el que se generó, porque es la deuda tal como se facturó.

## Relación con Gastos

Al **pagar** se crea un egreso real, así que ese monto aparece en [Gastos](12-gastos.md) con la entidad, la cuenta y la categoría del ítem. Ahí queda identificado como **gasto de presupuesto** (frente a los **libres**, cargados a mano en Movimientos).

Tres cosas a tener en cuenta:

- Gastos ordena por **fecha de pago**, no por el mes del presupuesto: si pagás en septiembre el ítem de agosto, suma a septiembre.
- Un ítem cerrado **en 0** no genera movimiento, así que no aparece en Gastos.
- Lo **pendiente** y lo **omitido** nunca están en Gastos (lo pendiente está en Pasivos). Por eso el total del mes en Presupuestos normalmente no coincide con el de Gastos, y está bien que no coincida.

## Relación con Pasivos

En Pasivos ves el **total pendiente por entidad** del mes actual y atrasados.  
Los meses futuros no aparecen ahí.  
Para liquidar el detalle, usá **Ir a Presupuestos** / **Ver**.

---

← [Patrimonio](04-patrimonio.md) · [Índice](README.md) · [Dashboard y snapshots](06-dashboard-y-snapshots.md) →
