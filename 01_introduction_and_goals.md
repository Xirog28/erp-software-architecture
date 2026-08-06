# 1. Introducción y Objetivos

El presente proyecto tiene como objetivo el diseño de la arquitectura de un Sistema ERP (Enterprise Resource Planning) que permita gestionar los procesos clave de una empresa de distribución: compras, facturación, stock/costos, activos fijos, empleados e información ejecutiva (EIS).

Este documento se centra en el **Módulo de Compras**, cuyos requisitos de negocio principales son:

- Registrar productos y proveedores.
- Asociar productos con proveedores y sus precios.
- Generar órdenes de compra.
- Registrar la recepción de mercancía y actualizar el inventario automáticamente.

## Objetivos de calidad
- **Usabilidad:** interfaz simple para gestores de compras y encargados de bodega.
- **Confiabilidad:** los datos de stock deben actualizarse correctamente tras cada recepción.
- **Escalabilidad:** la arquitectura debe permitir agregar los demás módulos del ERP a futuro.
