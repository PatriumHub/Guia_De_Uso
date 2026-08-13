# 2. Personas y empresas

## Personas

**Patrimonio → Personas**

- Representan a vos u otras personas físicas.
- Ahí ves tu patrimonio **personal**: cuentas a tu nombre + % de empresas.

### Crear una persona

1. **Personas** → **Nueva** (o similar).
2. Completá nombre (y doc/país si querés).
3. Guardá.
4. Entrá a la ficha para ver resumen, cuentas, activos, etc.

### En la ficha de una persona

Tenés pestañas: Resumen, Cuentas, Activos varios, Pasivos, Propiedades, Cobrables, Movimientos, Participaciones.

Arriba podés **Capturar snapshot** solo de esa persona.

### Eliminar una persona

1. **Personas** → **Editar**.
2. Abajo, sección roja **Eliminar persona**.
3. Escribí el nombre exacto y confirmá.

Se borran también cuentas, movimientos y demás datos de esa persona. No se puede deshacer.

## Empresas

**Patrimonio → Empresas**

- Negocios con cuentas, stock, ventas WC, valuación, dueños, etc.

### Crear una empresa

1. **Empresas** → nueva.
2. Nombre / razón social / rubro si aplica.
3. Elegí **Tipo de negocio**:
   - **Servicios** — Estados y proyección por cliente (como Soup IT).
   - **Productos** — solo total de ingresos por mes (como HomeSpot), sin lista de clientes.
4. Guardá y entrá al resumen.

### Eliminar una empresa

1. **Empresas** → **Editar**.
2. Abajo, sección roja **Eliminar empresa**.
3. Escribí el nombre exacto y confirmá.

Se borran cuentas, movimientos, estados y proyección, integraciones, etc. No se puede deshacer.

### Resumen de empresa (qué mirar)

- Patrimonio neto, activos, pasivos, liquidez.
- Bancos / líquido, saldo Mercado Pago, stock.
- Ventas WooCommerce y pedidos e-commerce (si hay sync).
- Formulario de **Movimiento de caja** (ingreso/egreso a una cuenta).

### Participaciones (dueños)

Para que el patrimonio **personal** sume un % de la empresa:

1. En la empresa → pestaña **Participaciones** (o menú **Participaciones**).
2. Alta: dueño (persona) + % de ownership.
3. En **Valuación** de la empresa, revisá o cargá el valor del negocio.

Sin participación cargada, la empresa no se “reparte” al patrimonio personal.

### Valuación de empresa

- Puede salir del libro (activos − pasivos) o de un override manual / sugerencia por ventas.
- Es lo que se usa para calcular “cuánto vale tu parte”.

### Estados y proyección

Pestaña de la **empresa** (no aparece en personas).

Sirve para planificar ingresos y costos mes a mes, con totales al instante — no mueve plata de las cuentas.

1. Entrá a la empresa → **Estados y proyección**.
2. Elegí el **año** (pills arriba).
3. Mirá el **dashboard**: ingresos anuales, egresos, balance, ahorro, ganancia neta.
4. Ingresos:
   - **Servicios:** tabla **Ingresos por cliente** (nombre + montos por mes).
   - **Productos:** una sola fila **Ingresos del mes** (total por mes).
5. Completá **Egresos / costos**.
6. El **Resumen mensual** se calcula solo.
7. Ajustá el **% de ahorro** si corresponde y tocá **Guardar** (o Ctrl+S).

Podés sumar clientes (servicios), costos o años. Si cambiás el tipo de negocio en Editar empresa, usá **Restablecer** en esta pestaña para regenerar la plantilla.

Cada empresa nueva recibe su libro automáticamente según el tipo elegido.

---

← [Primeros pasos](01-primeros-pasos.md) · [Índice](README.md) · [Cuentas y movimientos](03-cuentas-y-movimientos.md) →
