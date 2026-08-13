# 8. Configuración

**Tu nombre (arriba a la derecha) → Configuración**

## Mi perfil

Disponible para todos los usuarios.

- Cambiar **nombre** y **email** de login.
- Cambiar **contraseña** (pedís la actual + la nueva dos veces).

## Roles

| Rol | Acceso |
|-----|--------|
| **Administrador** | Control total: Inicio, Dashboard, Patrimonio, presupuestos, movimientos, integraciones, altas/ediciones/borrados |
| **Limitado (viewer)** | Solo lectura de las **personas y empresas asignadas**. Sin Inicio ni Dashboard. No puede crear, editar ni borrar nada |

### Usuario limitado

- Menú: **Personas**, **Empresas** y **Configuración** (solo perfil).
- Al entrar, va a Empresas o Personas según lo que tenga asignado.
- Ve fichas, tabs, estados y proyección, movimientos, etc., pero **sin botones de escritura**.
- Si intenta una URL de admin o un POST de escritura, el sistema lo redirige.

### Administrador

- Ve y opera toda la plataforma.
- Gestiona usuarios e integraciones.

## Usuarios (solo administradores)

Acá creás y editás usuarios del sistema.

### Crear un usuario

1. Configuración → **Usuarios**.
2. Completá nombre, email, contraseña, rol.
3. Si es limitado, tildá las **Personas** y **Empresas** que puede ver.
4. Creá usuario.

### Editar

En la tabla → **Editar**. Podés cambiar rol, acceso, activar/desactivar o poner una contraseña nueva (opcional).

> No te podés desactivar a vos mismo ni quitarte el único admin del sistema.

## Sistema (solo administradores)

- Link a **Integraciones** (WooCommerce).
- **Ocultar / mostrar cifras**.
- **Clave de cifrado** de integraciones (solo admin genera o rota).

---

## Tips

- El seed de instalación es `admin@patriumhub.local` / `admin123` — cambialo en **Mi perfil**.
- Un usuario limitado sin asignaciones solo ve Configuración → perfil; pedile a un admin que le asigne entidades.

---

← [WooCommerce e integraciones](07-woocommerce-e-integraciones.md) · [Índice](README.md) · [FAQ](09-preguntas-frecuentes.md) →
