# 10. Proyecciones

Menú **Proyecciones** (entre Dashboard y Patrimonio).

Vista **consolidada de solo lectura**: suma las planillas del año de personas y empresas.  
La carga se hace en cada ficha (persona → Proyecciones · empresa → Estados y proyección).

## Qué ves

| Bloque | Contenido |
|--------|-----------|
| Filtros | Año, alcance (Todas / Personas / Empresas), moneda |
| KPIs | Ingresos, egresos, balance, **promedio mensual** (disponible neto ÷ 12) |
| Realidad | Neto, liquidez y pasivos **reales** hoy + proyección de neto si se cumple el año |
| Flujo del año | Gráfico ancho de ingresos / egresos / balance mes a mes; debajo, personas vs empresas y por entidad |
| Ahorro proyectado | Total del año + mes a mes, acumulado y por entidad |
| Tablas | Personas y empresas con ingresos, egresos, ahorro y balance |
| Carga de egresos | Al final: egresos + ahorro + **disponible neto** (tras meta de ahorro; no presupuestos) |
| Gasto diario máximo | 12 cards: disponible neto del mes (balance − ahorro) ÷ días; referencia = promedio mensual ÷ 30 |

### Carga de egresos — menú consolidado

- **Egresos vs ingresos:** anillo del año + montos (egresos, ahorro proyectado, disponible neto).
- **Mes a mes:** barras apiladas — egresos (rojo ≥ 50% / gris &lt; 50%), ahorro (celeste) y disponible neto (verde).
- **Por entidad:** barras horizontales (entidad en Y, % en X), de mayor a menor carga.
- **Personas vs empresas:** % de carga por grupo.

### Carga de egresos — ficha persona

En **Persona → Proyecciones** el bloque va **después de la planilla** y además incluye:

- Anillo del año + leyenda con **cada egreso por nombre**, **ahorro** y **disponible neto**.
- Mes a mes (mismos colores que el consolidado).
- **Por categoría:** barras horizontales — nombre del egreso (línea de la planilla) y su % sobre los ingresos del año.

## Cómo cargar datos

1. **Persona** → pestaña **Proyecciones** → ingresos/egresos y % de ahorro → Guardar.  
2. **Empresa** → **Estados y proyección** → lo mismo según servicios o productos.  
3. Volvé a **Proyecciones** y elegí el año: se actualiza solo.

No mueve saldos de cuentas: es planificación.

## Tips

- Si una persona incluye utilidades de empresas en su planilla, puede haber solapamiento con la planilla de la empresa: usá el alcance o mirá las tablas por entidad.  
- **Ocultar cifras** también aplica acá.
- La **carga de egresos** usa los egresos de la planilla de proyección, no los gastos fijos de Presupuestos.
- El desglose **por categoría** solo aplica en la ficha de persona (usa los nombres de cada línea de egreso).
- El **gasto diario máximo** de cada card usa el **disponible neto de ese mes** (balance − ahorro) ÷ días 28/29/30/31. La línea ÷ 30 es solo referencia (promedio mensual ÷ 30).
- En **carga de egresos**, el verde es el disponible neto (ya descontado el ahorro); el celeste es la meta de ahorro.

---

← [Dashboard](06-dashboard-y-snapshots.md) · [Índice](README.md) · [Objetivos](11-objetivos.md) →
