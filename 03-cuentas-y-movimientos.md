# 3. Cuentas y movimientos

## Cuentas

**Patrimonio → Cuentas**

Acá están bancos, Mercado Pago, billeteras, efectivo, etc.  
**No hay un menú aparte de Mercado Pago**: es un tipo de cuenta más.

### Crear una cuenta

1. **Nueva cuenta**.
2. Elegí **titularidad**:
   - **Persona(s):** podés marcar varias y repartir el % (cuenta compartida).
   - **Empresa:** un solo dueño empresa.
3. Nombre, tipo (Banco, Mercado Pago, Efectivo…), moneda, saldo inicial.
4. Guardá.

El saldo se reparte en el patrimonio personal según el % de cada co-titular. En consolidado la cuenta cuenta una sola vez.

### Qué ves en Cuentas

- **Total en cuentas** (según moneda y filtro).
- **Cuentas bancarias** vs **Mercado Pago**.
- Gráficos por tipo y por titularidad (y gráficos MP si hay cuentas MP).
- Tabla con saldo y columna **Titularidad** (nombres + % si está compartida).
- En MP puede mostrarse “retenido” si lo cargaste.

### Eliminar una cuenta

Solo si **saldo y retenido están en 0**:

- Desde la tabla → **Eliminar**, o  
- Al editar la cuenta → sección eliminar.

Si tiene plata, transferí o ajustá a 0 antes.

### Ordenar

Clic en los encabezados de la tabla (flechas ↑ ↓).

---

## Movimientos

**Movimientos** (menú principal)

Sirven para registrar:

- **Ingreso** → suma al saldo de la cuenta  
- **Egreso** → resta  
- **Transferencia** → sale de una cuenta y entra en otra  
- **Ajuste** → corregís el saldo sin tratarlo como “gasto/ingreso” operativo  

### Crear un movimiento

1. **Nuevo movimiento**.
2. Entidad, tipo, fecha, importe, cuenta (y destino si es transferencia).
3. Categoría opcional. Hay varias de egreso listas: Comida, Salidas, Suscripciones, Limpieza, Higiene personal, Kiosco, Librería, Auto, Arreglos, Celular, Alquiler/es, Medicación & Farmacia, más Sueldos / Honorarios / Impuestos / Servicios.
4. Registrar.

### Editar un movimiento

En el listado → icono de **lápiz** (Editar), o abrí el movimiento y guardá cambios.

Podés cambiar **fecha, monto, tipo, cuentas, categoría, descripción**.  
Si cambiás monto/tipo/cuentas, el sistema **revierte el efecto viejo** y aplica el nuevo sobre los saldos.

### Eliminar un movimiento

En el listado → icono de **tachito** (rojo), o al editar → **Eliminar movimiento**.

Confirma: se **borra** el movimiento y se **recalculan los saldos** (se deshace el efecto en las cuentas).  
Si era el egreso de un presupuesto pagado, ese ítem vuelve a **pendiente**.

### Ordenar movimientos

Clic en las columnas del listado.  
Ordena lo que ves en la página actual (hay paginación).

### Tip práctico

- Si movés plata de banco a MP: usá **Transferencia** (no un egreso + un ingreso sueltos, salvo que quieras verlo así a propósito).
- Los movimientos de “caja” desde la empresa también piden una **cuenta**.
- En las tablas, las acciones son **iconos** (lápiz = editar, tachito = eliminar).
---

← [Personas y empresas](02-personas-y-empresas.md) · [Índice](README.md) · [Patrimonio](04-patrimonio.md) →
