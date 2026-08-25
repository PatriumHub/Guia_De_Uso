# 5. Presupuestos

Menú **Presupuestos**.

Sirve para los **gastos fijos / costos del mes** (alquiler, luz, internet, etc.).

## Conceptos

| Concepto | Significado |
|----------|-------------|
| **Gasto** (antes “plantilla”) | Se repite cada mes |
| **Ítem del mes** | La cuota de este período (pendiente / pagado / omitido) |
| **Gastos agrupados** | Todos los gastos activos, por persona o empresa |

Los **pendientes** del **mes actual y de meses atrasados** aparecen también en **Pasivos** (total por entidad).  
Si entrás a un mes **adelantado** (ej. septiembre estando en agosto), se generan los ítems para planificar, pero **no suman a pasivos** hasta que el calendario llegue a ese mes.

## Crear un gasto

1. Presupuestos → **+ Gasto** (o desde Gastos agrupados).
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
- **Omitir**: deja de contar como pasivo (no pagaste).
- **Revertir**: deshace el pago (anula el egreso y vuelve a pendiente).
- **Eliminar**: saca el ítem del mes y **desactiva** el gasto para que no se regenere (útil para algo de una sola vez).

## Gastos agrupados

Lista por entidad con totales.  
En cada grupo ves la tabla (ordená con clic en los títulos), **Eliminar grupo**, y dos gráficos: **composición** y **ranking** (mayor a menor %).  
Al cambiar **tema claro/oscuro**, los gráficos se actualizan solos (no hace falta recargar).  
Ahí podés **editar** o **eliminar** un gasto del grupo (deja de regenerarse; los pagos ya hechos se mantienen).

## Relación con Pasivos

En Pasivos ves el **total pendiente por entidad** del mes actual y atrasados.  
Los meses futuros no aparecen ahí.  
Para liquidar el detalle, usá **Ir a Presupuestos** / **Ver**.

---

← [Patrimonio](04-patrimonio.md) · [Índice](README.md) · [Dashboard y snapshots](06-dashboard-y-snapshots.md) →
