# 6. Dashboard y snapshots

## Dashboard

Menú **Dashboard**.

Vistas rápidas:

- **Consolidado** — todo junto, sin doble conteo por participaciones.  
- **Personal** — tu patrimonio (también hay un dashboard personal más simple).  
- **Liquidez** — foco en plata líquida vs el resto.

Podés filtrar por entidad, moneda y rango de fechas (movimientos/flujo).

### Capturar snapshot

Botón **Capturar snapshot** (arriba).

- Si **no** hay una entidad elegida: guarda consolidado + personal + **cada persona/empresa activa**.  
- Si hay entidad (o desde la ficha Persona/Empresa): guarda solo esa.

Eso alimenta la **evolución** en el tiempo y el gráfico de **variación por entidad**.

Si el gráfico de variación está vacío, usá **Capturar baseline ahora** en ese panel.

### ¿Cada cuánto capturar?

- A mano: cuando quieras un “punto de control” (fin de mes, después de un cambio grande).  
- Ideal: un **cron diario** en el servidor (`cron/snapshots.php`) para no olvidarte.

Con un solo snapshot por entidad ya podés ver variación contra el valor **actual**.  
Con dos o más, ves la diferencia entre capturas.

## Inicio

Resumen compacto de totales y accesos.  
No reemplaza al Dashboard para análisis.

## Exportar

En el Dashboard podés exportar la serie a CSV (evolución).

---

← [Presupuestos](05-presupuestos.md) · [Índice](README.md) · [WooCommerce](07-woocommerce-e-integraciones.md) →
