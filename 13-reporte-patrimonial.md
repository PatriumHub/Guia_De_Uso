# Reporte patrimonial mensual

Botón **Reporte**, arriba a la derecha (al lado de tu nombre).

Arma el cierre de un mes y lo deja listo para **imprimir o guardar como PDF**.

---

## Cómo se usa

1. Elegí **mes**, **alcance** y **moneda**.
2. Revisá el reporte en pantalla.
3. **Imprimir / PDF** → en el diálogo del navegador elegí *Guardar como PDF*.

El alcance puede ser **todas las entidades**, **todas las personas**, **todas las empresas** o **una entidad puntual**, igual que en Gastos.

---

## De dónde salen los números

**Todo se calcula con los datos que están cargados.** El reporte no usa la foto diaria de patrimonio: cada total es la suma de las líneas que ves debajo, así que siempre cierra consigo mismo y podés emitir **cualquier mes**, incluso anteriores a cuando arrancó el sistema de capturas.

El **corte** es el último día del mes, o **hoy** si el mes está en curso. Nada con fecha posterior al corte entra en el reporte, aunque ya lo hayas cargado: si registrás hoy un ingreso con fecha de mañana, el reporte de este mes no lo cuenta.

Qué tan histórico es cada número:

- **Cuentas**: el **saldo al corte**, reconstruido a partir de los movimientos. El saldo que ves en la pantalla de cuentas es el acumulado de todo lo cargado, sin importar la fecha; el reporte le descuenta lo que ocurre después del corte.
- **Cobrables**: las cuotas **exigibles al corte**. Las que vencen después no se cuentan todavía.
- **Presupuestos pendientes**: los del mes y los de meses anteriores sin liquidar.
- **Activos varios, propiedades, inventario, participaciones y deudas**: el **valor vigente**, porque de esas clases no se guarda histórico línea por línea.

El mes en curso sale marcado como **preliminar**: los números pueden cambiar hasta el cierre.

El reporte no escribe nada: no modifica meses pasados ni captura nada.

---

## Qué trae

| Sección | Contenido |
|---------|-----------|
| **Portada** | Mes, alcance, moneda, fecha de corte y de emisión |
| **Resumen** | Patrimonio neto, activos, pasivos, liquidez, y variación contra el mes anterior y contra el mismo mes del año pasado |
| **Composición y desglose del activo** | Las seis clases (cuentas, activos varios, propiedades, cobrables, inventario y participaciones) con su total y su %, y debajo de cada una, con sangría, el detalle línea por línea |
| **Composición y desglose del pasivo** | Deudas y presupuestos pendientes, con el mismo formato: total por grupo y detalle sangrado |
| **Desglose por entidad** | Activos, pasivos y neto de cada entidad (cuando el alcance abarca varias) |
| **Flujo del mes** | Ingresos, egresos y gastos, resultado y presupuesto planificado / pagado |
| **Egresos y gastos por categoría** | Gráfico de barras con el % de cada categoría, más la tabla con importes |
| **Notas metodológicas** | Criterios usados, para que el PDF se explique solo |

---

## Cosas a tener en cuenta

Lo **co-titularizado se prorratea** por porcentaje de titularidad, así que un activo compartido entre dos personas no se cuenta dos veces en el total.

Por eso mismo, **sumar a mano las filas del desglose por entidad puede no dar el total** del reporte: cada fila es la entidad por sí sola, mientras que en el total lo compartido se reparte y el neteo interno se descuenta una sola vez.

Cuando el alcance es *todas las entidades*, lo que una entidad del grupo le debe a otra aparece como una fila **Neteo interno** que resta en las dos tablas: es activo de una y pasivo de la otra, así que no puede sumar al patrimonio del conjunto.

El reporte trabaja con **una moneda por vez**, la que elijas en el filtro.

Las clases se listan **siempre todas, aunque estén en cero**, para que puedas comparar meses y alcances sin que cambie la estructura del reporte.

El **total de cada clase es la suma de sus líneas**, y el total del activo es la suma de las clases: no hay número que venga de otro lado.

En **Cobrables** va cada cuota pendiente con su vencimiento, ordenadas por fecha, y entran solo las que vencen dentro del mes del reporte o antes. Una cuota de diciembre no suma al activo de agosto, igual que un presupuesto de diciembre no suma al pasivo de agosto.

La **comparativa contra el mes anterior y el año anterior** recalcula esos meses con el mismo criterio. Como las clases sin histórico entran con su valor vigente en los tres meses, la variación refleja sobre todo cuentas, cobrables y presupuestos pendientes.

Las **participaciones** solo tienen detalle cuando el alcance es una persona o todas las personas: en el consolidado valen cero a propósito, para no contar dos veces el patrimonio de la empresa.

Una limitación a tener presente: el reporte de un mes pasado **no es del todo reproducible**. Las clases que no guardan histórico (activos varios, propiedades, inventario, participaciones y deudas) entran con su valor de hoy, así que si actualizás la tasación de una propiedad, el reporte de marzo emitido después va a mostrar el valor nuevo. Cuentas, cobrables y presupuestos sí quedan fijos.

---

← [Gastos](12-gastos.md) · [Índice](README.md) · [Preguntas frecuentes](09-preguntas-frecuentes.md) →
