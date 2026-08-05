# 5. Presupuestos

Menú **Presupuestos**.

Sirve para los **gastos fijos / costos del mes** (alquiler, luz, internet, etc.).

## Conceptos

| Concepto | Significado |
|----------|-------------|
| **Gasto** (antes “plantilla”) | Se repite cada mes |
| **Ítem del mes** | La cuota de este período (pendiente / pagado / omitido) |
| **Gastos agrupados** | Todos los gastos activos, por persona o empresa |

Los **pendientes** aparecen también en **Pasivos** (solo el total por entidad).

## Crear un gasto

1. Presupuestos → **+ Gasto** (o desde Gastos agrupados).
2. Entidad, nombre, monto (puede ser 0), día de vencimiento, cuenta sugerida.
3. Se genera el ítem del mes actual.

## Mes actual (pantalla principal)

- Filtrá por período y entidad.
- Ves pendientes, pagados y omitidos.
- Columnas ordenables (clic en el encabezado).

### Acciones por fila

| Estado | Qué podés hacer |
|--------|------------------|
| **Pendiente** | **Pagar** (rojo), Omitir, Eliminar |
| **Pagado** | Revertir, Eliminar |
| **Omitido** | Eliminar |

- **Pagar**: elegís cuenta e importe → crea un **egreso** y deja de contar como pasivo.  
  Si el monto es 0, cierra sin movimiento.
- **Omitir**: deja de contar como pasivo (no pagaste).
- **Revertir**: deshace el pago (anula el egreso y vuelve a pendiente).
- **Eliminar**: saca el ítem del mes y **desactiva** el gasto para que no se regenere (útil para algo de una sola vez).

## Gastos agrupados

Lista por entidad con totales.  
Ahí podés **editar** o **eliminar** un gasto del grupo (deja de regenerarse; los pagos ya hechos se mantienen).

## Relación con Pasivos

En Pasivos ves el **total pendiente por entidad**.  
Para liquidar el detalle, usá **Ir a Presupuestos** / **Ver**.

---

← [Patrimonio](04-patrimonio.md) · [Índice](README.md) · [Dashboard y snapshots](06-dashboard-y-snapshots.md) →
