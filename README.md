# tables-manager
Sistema de gestión de mesas para restaurantes, bares y cafés. Incluye panel interactivo, control de pedidos, métricas y automatizaciones.

Objetivos:

-Ver el plano de mesas y su estado en tiempo real.

-Tomar y editar comandas (items, notas) y enviarlas a cocina.

-Registrar ventas y exportar a CSV/Excel.

MVP:

-Panel visual de mesas (drag & drop para layout).

-Estados de las mesas (LIBRE, OCUPADA, ESPERANDO_PEDIDO, SERVIDA).

-Crear/editar comandas (Producto, Cantidad, Notas).

-Módulo Cocina (ver comandas, marcar en preparación / listo).

-Export CSV / Excel de ventas.

-Login multi-rol (Admin, Mozo, Cocina).

-Guardado del layout de mesas por UI.

-Dashboard simple: ventas del día, mesas ocupadas, ticket promedio.

-Pantalla solo visual.

ARQUITECTURA Y STACK:

Frontend: React + Vite + TypeScript (PWA ready) + Tailwind.

Backend: Node.js + NestJS (o Express) + TypeORM/Prisma.

BD: PostgreSQL (cloud) + SQLite para offline/local.

Realtime: WebSockets / Socket.IO.
