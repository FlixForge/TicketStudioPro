<div align="center">

  <img src="assets/logo.png" alt="Ticket Studio Pro Logo" width="140" />

  # Ticket Studio Pro

  ### **Sistema POS de Escritorio & Generación de Tickets Térmicos**
  *Una solución rápida, moderna y 100% offline diseñada para el control total de ventas e inventario.*

  [![Demo Live](https://img.shields.io/badge/🌐_Landing_Page-Ver_Demostración-2563eb?style=for-the-badge)](https://FlixForge.github.io/TicketStudioPro/)
  [![Estado](https://img.shields.io/badge/Estado-Demostración_Oficial-blue?style=for-the-badge)](#)
  [![Licencia](https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge)](#)

</div>

---

## 📌 Descripción General

**Ticket Studio Pro** es un sistema de Punto de Venta (POS) de escritorio con interfaz oscura moderna, rápida y adaptable. Está pensado para pequeños y medianos comercios que buscan emitir tickets de compra impresos o digitales en segundos, gestionar productos con código de barras, controlar cortes de caja, administrar cajeros y llevar un control claro de sus ingresos.

Este repositorio corresponde a la **versión de demostración del software y presentación del proyecto**.

---

## ✨ Características Principales

* 🚀 **Módulo de Venta Inmediata:** Cobro fluido en caja con calculo de cambio instantáneo, atajos rápidos de efectivo (`+$50`, `+$100`, etc.), acceso táctil a productos favoritos y búsqueda por lector de código de barras.
* 💵 **Corte de Caja:** Control completo de apertura y cierre de turno, cálculo de efectivo esperado, desglose por ventas en efectivo, tarjetas y transferencias, registro de entradas/retiros, control de efectivo físico real y detección de sobrantes o faltantes, además de consulta de cortes anteriores.
* 👥 **Gestión de Cajeros y Accesos:** Registro de operadores, activación o desactivación de cuentas, asignación de roles de cajero o administrador, y control estricto de acceso mediante PIN numérico desde la sección de configuración.
* 📄 **Tickets Termales de 80mm:** Renderizado en tiempo real de recibos con soporte para exportación directa a **PDF** o imágenes **PNG** de alta calidad.
* 🏷️ **Catálogo de Productos & Generador EAN-13:** Control de inventarios con sistema de alerta de stock mínimo, calculador automático de margen de ganancias e integración de generador de código de barras estándar **EAN-13**.
* 📊 **Historial Comercial & Exportación CSV:** Filtros de ingresos por rango de fechas, resumen de métodos de pago (Efectivo, Tarjeta, Transferencia), control de IVA retenido y exportación directa de reportes a Excel/CSV.
* 🎨 **Personalización Total:** Incorpora el logotipo de tu marca, datos fiscales (RFC/NIT), dirección, mensaje al pie de página y un **código QR dinámico** con enlace a Google Maps o redes sociales.
* 🔒 **100% Offline & Privado:** Arquitectura local basada en SQLite. Sin cobros mensuales ni dependencia de conexión a internet.

---

## 📸 Capturas de Pantalla e Interfaz

### 🛒 1. Módulo de Venta POS
> Interfaz optimizada para agilizar cobros continuos, selección rápida de productos y previsualización en tiempo real del ticket térmico.

![Módulo de Venta](assets/venta.png)

---

### 💵 2. Cortes de Caja
> Pestaña dedicada al control de apertura y cierre de turno, arqueo de caja, desglose detallado de cobros y consulta del historial de cortes.

![Cortes de Caja](assets/caja.png)

---

### 📦 3. Catálogo e Inventario
> Vista de productos con indicadores visuales de stock, filtrado por categorías y vista previa del ticket comercial.

![Catálogo e Inventario](assets/catalogo.png)

---

### ➕ 4. Formulario de Producto & Creador de Código de Barras EAN-13
> Alta de artículos con cálculo de margen estimado, definición de stock mínimo para alertas y generador automático de código EAN-13.

<div align="center">
  <img src="assets/catalogo_ventana.png" alt="Nuevo Producto" width="650" />
</div>

---

### 👥 5. Gestión de Cajeros y Accesos
> Módulo dentro de Ajustes/Configuración para registrar cajeros, asignar contraseñas PIN, definir roles de seguridad y activar o desactivar cuentas.

<div align="center">
  <img src="assets/gestion-cajeros.png" alt="Gestión de Cajeros" width="650" />
</div>

---

### 📈 6. Historial de Ventas & Totales
> Consulta de transacciones pasadas, desglose por IVA retenido, métodos de pago y exportación de reportes tabulares a CSV.

![Historial de Ventas](assets/historial.png)

---

### ⚙️ 7. Configuración Comercial & Estilo del Ticket
> Configuración completa de la identidad del negocio: carga de logotipo, dirección, QR personalizado, fuentes y tamaño de papel.

![Configuración](assets/configuracion.png)

---

## 🛠️ Stack Tecnológico

* **Lenguaje Principal:** Python 3.x
* **Interfaz Gráfica:** PyQt6 / PySide6 (Tema Oscuro Personalizado)
* **Base de Datos Local:** SQLite 3
* **Generación de Documentos:** ReportLab (Motor PDF) & Pillow (Exportación PNG)
* **Generador QR & Códigos:** QRCodegen & Python-Barcode

---

## 📄 Licencia

Este proyecto y sus materiales de demostración están bajo la Licencia **MIT**. Consulta el archivo `LICENSE` para más información.

<div align="center">

Desarrollado para demostración técnica de **Ticket Studio Pro**.

</div>
