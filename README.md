# 🎟️ Ticket Studio Pro

<p align="center">
  <img src="logo.png" alt="Ticket Studio Pro Logo" width="120" style="border-radius: 24px;">
</p>

<p align="center">
  <b>Sistema de Punto de Venta (POS) & Generador de Tickets Térmicos de 80mm</b>
</p>

<p align="center">
  <a href="#-características-principales">Características</a> •
  <a href="#-capturas-de-pantalla">Capturas</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-licencia">Licencia</a>
</p>

---

## 📌 Descripción General

**Ticket Studio Pro** es una aplicación de escritorio moderna, rápida y 100% offline diseñada para simplificar el cobro, la gestión de productos y la emisión de tickets térmicos en pequeños y medianos negocios.

Desarrollada con un diseño oscuro elegante y con acentos azul neón, la aplicación permite cobros inmediatos, generación instantánea de tickets en **PDF** o **PNG** con código QR personalizado y lectura/creación de códigos de barra **EAN-13**.

---

## ✨ Características Principales

- 🚀 **Módulo de Venta Inmediata:** Cobro rápido con atajos de billetes (`+$50`, `+$100`, etc.), búsqueda instantánea por SKU o nombre y panel táctil de productos favoritos.
- 📄 **Tickets de 80mm en Tiempo Real:** Previsualización dinámica del recibo e impresión térmica instantánea. Exporta también en archivo **PDF** o imagen **PNG**.
- 🏷️ **Catálogo & Generador EAN-13:** Control de inventarios con stock mínimo (alertas), cálculo automático de margen de beneficio y generador interno de códigos de barras.
- 📊 **Historial & Exportación CSV:** Consulta de ingresos por fecha (Efectivo, Tarjeta, Transferencia), control de IVA retenido y exportación directa de reportes a Excel/CSV.
- 🎨 **Personalización Comercial:** Define tu logotipo, datos de la empresa (RFC/NIT), dirección, mensaje al pie de página y QR dinámico con redirección a Google Maps o redes sociales.
- 🔒 **100% Offline & Privado:** Todos tus registros permanecen en tu equipo mediante una base de datos local SQLite. Sin suscripciones ni conexión a internet obligatoria.

---

## 📸 Capturas de Pantalla

### 🛒 1. Módulo de Venta POS
Vista principal optimizada para agilizar los cobros en caja con cálculo automático de cambio.
![Módulo de Venta](Pestaña%20Venta.png)

### 📦 2. Catálogo e Inventario
Administración clara con estados de stock en color verde/rojo según alertas.
![Catálogo e Inventario](Pestaña%20Catalogo.png)

### ➕ Formulario de Producto con EAN-13
Generación automática de códigos de barras EAN-13 estándar para tus productos.
![Nuevo Producto](Pestaña%20Catalogo%20Ventana.png)

### 📈 3. Historial de Ventas & Totales
Revisión rápida de folios emitidos y filtros por rango de fechas.
![Historial de Ventas](Pestaña%20Historil.png)

### ⚙️ 4. Configuración & Estilo del Ticket
Carga de logo, pie de página, tamaño de papel y fuentes tipográficas.
![Configuración del Ticket](Configuracion.png)

---

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Python 3.x
- **Interfaz Gráfica:** PyQt6 / PySide6
- **Base de Datos:** SQLite 3
- **Librerías de Ticket:** ReportLab (PDF) / Pillow (PNG) / QRCodegen
- **Empaquetado:** PyInstaller + Inno Setup

---

## 🚀 Instalación y Uso Local

### Prerrequisitos
- Python 3.10 o superior instalado.

### Clonar e instalar dependencias

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/ticket-studio-pro.git

# Entrar al directorio
cd ticket-studio-pro

# Crear un entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate  # En Windows usa: venv\Scripts\activate

# Instalar requerimientos
pip install -r requirements.txt

# Ejecutar la aplicación
python main.py
```

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Puedes consultar el archivo `LICENSE` para obtener más información.