# 🗄️ **Análisis Comercial con SQL – Modelado, KPIs y Consultas**

🎯 **Objetivo del proyecto**  
Construir un análisis comercial completo utilizando SQL, aplicando consultas de segmentación, KPIs, métricas de ventas, análisis de productos, clientes, vendedores y sucursales.

📁 **Conjunto de datos utilizado**
- **CLIENTES**: segmento, provincia, contacto, estado  
- **PRODUCTOS**: categorías, marcas, costos, precios  
- **CATEGORIAS**: clasificación de productos  
- **VENDEDORES**: sucursal, supervisor, comisiones  
- **SUCURSALES**: región y ubicación  
- **VENTAS**: fecha, canal, medio de pago, vendedor  
- **DETALLE DE VENTAS**: productos vendidos, cantidades, precios  

---

## 🧱 **Modelo de datos**
Tablas relacionadas por:
- ClienteID  
- ProductoID  
- VendedorID  
- SucursalID  
- CategoriaID  

Relación tipo **modelo estrella** para análisis comercial.

---

## 📊 **Consultas SQL desarrolladas**

### **Clientes**
- Cantidad de clientes por provincia  
- Cantidad por segmento  
- Segmento + provincia  
- Clientes sin email o teléfono  
- Información de contacto

### **Productos**
- Cantidad total de productos  
- Productos por categoría  
- Productos por subcategoría  
- Productos por marca  
- Costos mínimo, máximo y promedio  
- Precio de lista mínimo y máximo  
- Margen por producto  
- Costo promedio por categoría y marca  

### **Vendedores**
- Vendedores por sucursal  
- Vendedores por supervisor  
- Cantidad de vendedores por sucursal  
- Vendedores activos

### **Ventas**
- Ventas totales por año  
- Ventas por sucursal  
- Ventas por medio de pago  
- Ventas por canal  
- Ventas por vendedor  
- Comparativa 2025 vs 2026  

---

## 📈 **KPIs generados**
- **Clientes totales**  
- **Productos activos vs descontinuados**  
- **Costo promedio por categoría**  
- **Margen promedio por marca**  
- **Ventas por sucursal**  
- **Ventas por canal**  
- **Ventas por vendedor**  
- **Top productos por precio y costo**  

---

## 🔍 **Insights obtenidos**
- Buenos Aires concentra la mayor cantidad de clientes.  
- Las categorías con más productos son Tecnología y Muebles.  
- Marcas como PixelOne, Vision y AirFlow tienen mayor presencia.  
- Los vendedores de sucursales del Sur y Centro tienen mayor volumen de ventas.  
- Los productos descontinuados representan una proporción menor pero relevante para análisis de stock.  
- Las ventas 2026 muestran crecimiento respecto a 2025 en la mayoría de sucursales.

---

## 🛠️ **Herramientas utilizadas**
- SQL Server / MySQL (compatible)  
- Consultas avanzadas  
- Funciones agregadas  
- Subconsultas  
- Ordenamientos y filtros  
- Joins (si se agregan más consultas)  

---

## 📁 **Estructura del repositorio**
