# 7. WooCommerce e integraciones

## Dónde está

**Tu nombre** → **Configuración** → botón **Abrir integraciones**  
(o la URL de integraciones).

Las conexiones **no van en el archivo `.env`**.  
Mercado Pago **no** se conecta por API en la v1: es una **cuenta manual** en Cuentas.

## WooCommerce

Sirve para traer:

- Ventas / pedidos  
- Inventario (stock valuado)  

### Conectar

1. Configuración → Integraciones → **+ WooCommerce**.
2. Asociá la **empresa**.
3. Pegá URL de la tienda + Consumer Key / Secret.
4. Probá la conexión y corré un **sync**.

Antes, en Configuración, asegurate de tener la **clave de cifrado** generada (guarda las keys cifradas en la base).

### Qué vas a ver después

- En la **empresa**: ventas WooCommerce, pedidos e-commerce, stock.  
- En gráficos del resumen de empresa.

Si el sync falla, revisá URL, keys y que la clave de cifrado exista. Podés volver a **probar** o **sync** desde la ficha de la integración.

## Mercado Pago

1. **Cuentas** → Nueva cuenta → tipo **Mercado Pago**.  
2. Cargá el saldo a mano.  
3. Los movimientos sobre esa cuenta se cargan como cualquier otro (ingreso/egreso/transferencia).

Los gráficos de MP están dentro de **Cuentas**, no en un sitio aparte.

---

← [Dashboard](06-dashboard-y-snapshots.md) · [Índice](README.md) · [Configuración](08-configuracion.md) →
