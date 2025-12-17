# 🏢 Sistema de Gestión Empresarial

Aplicación de escritorio desarrollada para la **administración integral de procesos empresariales**, orientada al control eficiente de clientes, empleados, ventas, inventario, proveedores, sucursales y reportes analíticos, todo desde una interfaz clara e intuitiva.

---

## 📌 Descripción del Proyecto

El **Sistema de Gestión Empresarial** es una solución diseñada para centralizar y optimizar la gestión administrativa de una empresa.  
El sistema permite manejar información crítica de forma estructurada, segura y accesible, facilitando la toma de decisiones mediante reportes gráficos y visualización organizada de datos.

Está orientado a **pequeñas y medianas empresas**, así como a fines **académicos y de demostración profesional**.

---

## 🔐 Autenticación y Control de Acceso

- Inicio de sesión mediante usuario y contraseña
- Validación de credenciales
- Bloqueo de acceso ante datos incorrectos
- Mensajes de error controlados
- Acceso seguro previo a la aplicación principal

---

## 👥 Gestión de Clientes

- Registro de clientes
- Edición rápida mediante doble clic
- Eliminación con confirmación
- Visualización en tabla (TreeView)
- Importación de clientes desde archivos CSV
- Exportación de datos a formato CSV

---

## 🧑‍💼 Gestión de Empleados

- Operaciones CRUD completas
- Cambio de estado:
  - ✅ Activo
  - ❌ Inactivo
- Identificación visual del estado
- Confirmaciones antes de eliminar registros

---

## 💰 Gestión de Ventas

- Registro de ventas
- Asociación de clientes y productos
- Historial de transacciones
- Integración directa con inventario
- Acciones rápidas sobre cada registro

---

## 📄 Detalles de Ventas

- Visualización detallada de cada transacción
- Productos vendidos
- Cantidades y montos
- Apoyo a procesos de auditoría y control interno

---

## 📦 Gestión de Inventario

- Administración completa de productos
- Control de stock en tiempo real
- Indicadores visuales:
  - 🟢 Stock alto
  - 🟡 Stock medio
  - 🔴 Stock bajo
- Prevención de desabastecimiento

---

## 🗂 Gestión de Categorías

- Registro de categorías
- Edición y eliminación
- Organización del inventario
- Relación directa con productos

---

## 🏢 Gestión de Sucursales

- Registro de sucursales
- Edición y eliminación
- Funcionamiento similar al módulo de empleados
- Administración centralizada de múltiples sedes

---

## 🚚 Gestión de Proveedores

- Registro de proveedores
- Edición y eliminación
- Organización de contactos comerciales
- Relación con productos

---

## 📊 Módulo de Reportes

Generación de reportes gráficos para análisis empresarial:

- 📈 Ganancias totales por período
- 📊 Productos más vendidos
- 📉 Clientes únicos por sucursal
- Gráficos claros para apoyo a la toma de decisiones

---

## 🛠 Tecnologías Utilizadas

- 🐍 **Python**
- 🖥 **Tkinter** (interfaz gráfica)
- 🗄 **SQLite** (base de datos)
- 📊 **Matplotlib** (reportes gráficos)
- 📁 **CSV** (importación y exportación de datos)
- 🔐 **dotenv** (variables de entorno)

---

## 🧠 Arquitectura del Sistema

- Diseño modular
- Separación de responsabilidades
- Uso de clases para cada módulo
- Manejo de errores y validaciones
- Flujo de inicio seguro mediante login

---

## 🔐 Seguridad

- Autenticación obligatoria
- Confirmación antes de eliminar información
- Manejo controlado de excepciones
- Protección de datos sensibles mediante variables de entorno

---

## 👨‍💻 Autor

**Luis Alberto Rojas**  
Proyecto de Gestión Empresarial  
Aplicación de escritorio desarrollada en Python

---

## 📌 Estado del Proyecto

- ✅ Proyecto finalizado
- 🚀 Funcional y estable
- 🎓 Apto para evaluación académica
- 📦 Escalable para futuras mejoras (web, API, multiusuario)
