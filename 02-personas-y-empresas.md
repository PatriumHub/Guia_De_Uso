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

Tenés pestañas: Resumen, **Proyecciones**, Cuentas, Activos varios, Pasivos, Propiedades, Cobrables, Movimientos, Participaciones.

Arriba podés **Capturar snapshot** solo de esa persona.

### Eliminar una persona

1. **Personas** → **Editar**.
2. Abajo, sección roja **Eliminar persona**.
3. Escribí el nombre exacto y confirmá.

Se borran también cuentas, movimientos y demás datos de esa persona. No se puede deshacer.

### Proyecciones (persona)

Pestaña para planificar **ingresos, egresos y ahorro** mes a mes (pasados o futuros).

1. Entrá a la persona → **Proyecciones**.
2. Cargá fuentes de ingreso (sueldo, honorarios, etc.) y gastos por mes; ajustá el % de ahorro.
3. El sistema calcula balance, ahorro, disponible y **promedio mensual** (disponible neto anual ÷ 12), y lo compara con tu **neto, liquidez y pasivos reales**.
4. En **Resumen** ves un resumen rápido de la proyección del año activo.

No mueve saldos de cuentas: es planificación.  
La vista del menú **Proyecciones** suma esta planilla con las de las empresas. Ver [Proyecciones consolidadas](10-proyecciones.md).

## Empresas

**Patrimonio → Empresas**

- Negocios con cuentas, stock, ventas WC, valuación, dueños, etc.

### Crear una empresa

1. **Empresas** → nueva.
2. Nombre / razón social / rubro si aplica.
3. Elegí **Tipo de negocio** (solo se elige al crear; después no se cambia):
   - **Servicios** — Estados y proyección por cliente + pestaña **Clientes** (como Soup IT).
   - **Productos** — solo total de ingresos por mes (como HomeSpot), sin lista de clientes.
4. Guardá y entrá al resumen.

### Eliminar una empresa

1. **Empresas** → **Editar**.
2. Abajo, sección roja **Eliminar empresa**.
3. Escribí el nombre exacto y confirmá.

Se borran cuentas, movimientos, estados y proyección, fichas de clientes, integraciones, etc. No se puede deshacer.

### Resumen de empresa (qué mirar)

- Patrimonio neto, activos, pasivos, liquidez.
- Bancos / líquido, saldo Mercado Pago, stock.
- Ventas WooCommerce y pedidos e-commerce (si hay sync).
- Formulario de **Movimiento de caja** (ingreso/egreso a una cuenta).

### Clientes (solo empresas de servicios)

Pestaña de la empresa de **servicios**. La lista y los montos salen de **Estados y proyección**; acá completás la ficha operativa.

1. Entrá a la empresa → **Clientes**.
2. Vas a ver KPIs (activos / inactivos / total) y la tabla.
3. Abrí un cliente → **Ver** o **Ficha** para cargar:
   - Contacto, email, teléfono y notas.
   - Estado **activo** / **inactivo**.
   - **Contrato** (solo PDF).
   - Documentos extra (PDF, imágenes u Office).
4. Para agregar o renombrar clientes o cambiar montos: andá a **Estados y proyección**, editá las filas y **Guardá**. Al volver a Clientes se sincroniza.

Los usuarios limitados (viewer) pueden ver, pero no editar ni subir archivos.

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

Podés sumar clientes (servicios), costos o años. En empresas de servicios, los nombres de cliente de esta tabla alimentan la pestaña **Clientes**.

Cada empresa nueva recibe su libro automáticamente según el tipo elegido al crear.  
Esa planilla también entra en el menú **Proyecciones** (consolidado). Ver [Proyecciones](10-proyecciones.md).

---

← [Primeros pasos](01-primeros-pasos.md) · [Índice](README.md) · [Cuentas y movimientos](03-cuentas-y-movimientos.md) →
