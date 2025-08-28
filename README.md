# 🛒 Sale Bundle Kits (Paquetes de Productos) - Odoo 18.0

Este módulo permite **crear y vender paquetes (combos) de productos** en Odoo.  
Cuando se vende un combo, el sistema descuenta automáticamente el inventario de cada producto incluido en él.  

---

## ✨ Características

✅ Crear productos tipo **Bundle (Paquete)**.  
✅ Definir fácilmente qué productos y cantidades forman parte del paquete.  
✅ Al confirmar una venta:
- Se agrega el paquete a la orden.
- El inventario se descuenta por cada producto incluido.  
✅ Compatible con:
- Ventas (`sale`).
- Facturación (`account`).
- Inventario (`stock`).  

---

## 📸 Ejemplo de Uso

1. Crear un producto tipo **Bundle** (ej. *Canasta Básica*).  
2. Definir los componentes del bundle:
   - 1 x Aceite
   - 2 x Maíz
   - 1 x Frijol
   - 1 x Azúcar  
3. Al vender la *Canasta Básica*, Odoo genera la orden y descuenta stock de **Aceite, Maíz, Frijol y Azúcar**.  

📷 *(Aquí puedes agregar capturas de pantalla de tu Odoo una vez lo tengas funcionando en SH, por ejemplo la vista del producto con sus componentes y una orden de venta con el bundle).*  

---

## ⚙️ Instalación en Odoo SH

1. Clonar este repositorio en tu proyecto Odoo SH dentro de la carpeta `odoo_addons/`.  
   ```bash
   git clone https://github.com/TU_USUARIO/sale_bundle_kits.git odoo_addons/sale_bundle_kits
