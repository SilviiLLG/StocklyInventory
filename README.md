# STOCKLY — Inventory Control

Demo frontend de gestión de inventario desarrollada para el portfolio de Teknovya.

## Funcionalidades
- Dashboard con productos, unidades, valor de inventario y alertas.
- Alta, edición, búsqueda, filtrado y eliminación de productos.
- SKU único para evitar duplicados.
- Categorías, precio de costo, precio de venta, stock actual y mínimo.
- Registro de entradas y salidas con validación de stock disponible.
- Historial de movimientos.
- Alertas automáticas de stock bajo y agotado.
- Agenda de proveedores.
- Reportes de valorización, margen bruto potencial y unidades por categoría.
- Exportación del catálogo a CSV.
- Persistencia local con `localStorage`.
- Diseño responsive para celular y escritorio.
  
## Importante: alcance de esta demo
Esta versión funciona completamente en el navegador y guarda la información en `localStorage`. No tiene usuarios reales, base de datos compartida ni sincronización entre dispositivos. Los datos iniciales son ficticios. Para usarla en un comercio real habría que agregar backend, base de datos, autenticación, permisos, copias de seguridad y controles de auditoría.
