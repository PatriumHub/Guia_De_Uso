# 9. Preguntas frecuentes

## ¿Por qué mi neto personal no es la suma de todas las empresas?

Porque en **personal** solo entra tu % (participaciones) más lo que está a tu nombre.  
El **consolidado** mira el conjunto sin inflar por ownership.

## ¿Dónde está Mercado Pago?

En **Cuentas**, tipo Mercado Pago. Ya no hay un menú aparte.

## Hice un ingreso de caja y “En caja” no existía / no subía

Correcto en v1: todo va a una **cuenta**. El saldo se ve en **Bancos / líquido** o en el total de esa cuenta (si es efectivo, tipo Efectivo).

## Pagué un presupuesto por error

En Presupuestos → **Revertir**. Después podés pagar de nuevo o eliminar.

## Miré el presupuesto de un mes futuro y me bajó el patrimonio

No debería. Solo suman a pasivos los pendientes del **mes actual y atrasados**.  
Si ves un mes adelantado, es para planificar; el neto se actualiza cuando llegue ese mes. Refrescá Pasivos / Dashboard si quedó un dato viejo en caché del navegador.

## Quiero un gasto de una sola vez

Creá el gasto, usalo el mes que haga falta, y **Eliminar** (en el mes o en Gastos agrupados) para que no se regenere.

## No puedo borrar una cuenta

Tiene que tener **saldo 0** y **retenido 0**.

## El gráfico “Variación por entidad” está vacío

Todavía no hay snapshots por entidad. En el Dashboard usá **Capturar snapshot** o **Capturar baseline ahora**.

## Cambié un movimiento y el saldo de la cuenta se movió solo

Es esperado: editar importe/tipo/cuenta **recalcula** el saldo.

## ¿Puedo ordenar tablas?

Sí, en Presupuestos, Cuentas y Movimientos: clic en el título de la columna.

## ¿Puedo compartir una cuenta entre dos personas?

Sí. En **Cuentas** → editar/crear → titularidad **Persona(s)** → marcá las personas y el %.  
Cada una suma solo su parte al patrimonio personal; en consolidado no se duplica.

## ¿Dónde veo el flujo de todas las planillas juntas?

Menú **Proyecciones**: consolida personas y empresas del año (solo lectura).  
La carga es en cada ficha. Ver [Proyecciones](10-proyecciones.md).

## ¿Dónde cargo la proyección de clientes / costos de la empresa?

En la empresa → pestaña **Estados y proyección**. Es planificación (no mueve saldos).  
Si la empresa es de **productos**, cargás solo el total de ingresos por mes (sin clientes). Ver [Personas y empresas](02-personas-y-empresas.md).

## ¿Dónde cargo contacto, contrato o docs de un cliente?

En empresas de **servicios** → pestaña **Clientes** → ficha del cliente.  
La lista y los montos vienen de **Estados y proyección**; acá vas el contacto, activo/inactivo, contrato PDF y documentos extra. Ver [Personas y empresas](02-personas-y-empresas.md).

## ¿Puedo cambiar el tipo de negocio (servicios / productos) después?

No. Se elige solo al **crear** la empresa. Si te equivocaste, hay que crear otra con el tipo correcto.

## ¿Cómo creo otro usuario o limito qué ve?

**Configuración → Usuarios** (solo admin). Rol limitado + tilde de personas/empresas. Ese usuario solo **ve** lo asignado (sin crear/editar/borrar, sin Inicio ni Dashboard). Ver [Configuración](08-configuracion.md).

## ¿Cómo borro una persona o empresa?

**Editar** → abajo **Eliminar** → escribí el nombre exacto. Se va todo lo asociado. Ver [Personas y empresas](02-personas-y-empresas.md).

## ¿Por qué personal y consolidado no dan igual?

En personal solo entra tu %. La diferencia suele ser la parte de empresas que no te pertenece (ej. el otro 50 % de Soup IT).

## ¿La app reemplaza a mi contador?

No. Es una herramienta de **control patrimonial y liquidez** para vos. No es un sistema contable impositivo.

---

## Checklist rápido fin de mes

1. Revisar saldos de **Cuentas** (banco + MP).  
2. Liquidar o omitir **Presupuestos** del mes.  
3. Actualizar **Proyecciones** personales y **Estados y proyección** de cada empresa si aplica.  
4. Mirar el menú **Proyecciones** (flujo y ahorro del año).  
5. En servicios: revisar fichas en **Clientes** (estado, contratos).  
6. Sync de **WooCommerce** si aplica.  
7. **Capturar snapshot** en el Dashboard.  
8. Mirar neto personal vs consolidado.

---

← [Configuración](08-configuracion.md) · [Índice](README.md)
