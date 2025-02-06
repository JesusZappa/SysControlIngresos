# SysControlIngresos
El Sistema de Control de Ingresos optimiza la gestión de talleres mecánicos, permitiendo registrar clientes y vehículos, crear órdenes de trabajo, administrar inventario y facturación. Incluye control de empleados, citas, reportes y seguridad con acceso por roles. Integrado con notificaciones, facilita la eficiencia operativa


Descripción Base del Proyecto
Nombre del Proyecto:
Sistema de Control de Ingresos y Bitácora de Seguimiento para Talleres Mecánicos

Objetivo General:
Desarrollar un sistema integral en Python que permita gestionar el control de ingreso de vehículos a un taller mecánico, facilitando el registro de clientes, vehículos, órdenes de trabajo, inventario, facturación y reportes. El sistema busca optimizar los procesos administrativos y operativos del taller, mejorando la eficiencia en la gestión de servicios y la comunicación con los clientes.

Funcionalidades Principales:

Gestión de Clientes:
Registro, edición y eliminación de clientes.
Asociación de vehículos a clientes.
Historial de servicios por cliente.
Notificaciones automáticas (correo o SMS) sobre el estado del vehículo.

Gestión de Vehículos:
Registro de vehículos con detalles como placa, marca, modelo y año.
Historial de mantenimientos y reparaciones.
Alertas programadas para próximos mantenimientos.

Gestión de Órdenes de Trabajo:
Creación, modificación y cierre de órdenes de trabajo.
Asignación de mecánicos a órdenes específicas.
Registro de diagnósticos, repuestos utilizados y servicios realizados.
Adjuntar fotos o documentos relacionados.
Generación de presupuestos y aprobación por parte del cliente.
Inventario y Control de Repuestos:
Registro y control de repuestos y herramientas en el almacén.
Notificaciones de stock bajo.
Asociación de repuestos a órdenes de trabajo.
Control de entradas y salidas del almacén.

Facturación y Pagos:
Generación de facturas electrónicas.
Registro de métodos de pago (efectivo, tarjeta, transferencia).
Control de cuentas por cobrar.
Aplicación de descuentos y promociones.
Gestión de Empleados:
Registro de mecánicos y administradores.
Control de asistencia y horarios.
Asignación de tareas y órdenes de trabajo.
Historial de trabajos realizados por empleado.

Reportes y Estadísticas:
Reportes de ingresos y egresos.
Estadísticas de servicios más solicitados.
Reportes de productividad de empleados.
Reporte de repuestos más utilizados.

Agenda y Citas:
Programación de citas para mantenimientos o reparaciones.
Notificación automática al cliente antes de su cita.
Integración con calendarios externos.
Integraciones y Seguridad:
Integración con WhatsApp o correo para notificaciones.
Control de acceso por roles (administrador, mecánico, recepcionista).

Copias de seguridad automáticas.

Tecnologías y Herramientas Propuestas:
Lenguaje de Programación: Python.
Interfaz Gráfica: Tkinter, PyQt o Streamlit (dependiendo de la complejidad y preferencia).
Base de Datos: SQLite, MySQL o PostgreSQL.
Control de Versiones: Git y GitHub/GitLab.

Notificaciones: Integración con APIs de correo (SMTP) o SMS (Twilio).
Reportes: Uso de bibliotecas como Pandas y Matplotlib para generación de gráficos y estadísticas.

Estructura del Proyecto:
Módulo de Clientes: Gestión de datos de clientes y sus vehículos.
Módulo de Vehículos: Registro y seguimiento de vehículos.
Módulo de Órdenes de Trabajo: Creación y gestión de órdenes de servicio.
Módulo de Inventario: Control de repuestos y herramientas.
Módulo de Facturación: Generación de facturas y gestión de pagos.
Módulo de Empleados: Registro y asignación de tareas a empleados.
Módulo de Reportes: Generación de reportes y estadísticas.
Módulo de Agenda: Programación y notificación de citas.
Módulo de Seguridad: Control de acceso y copias de seguridad.
