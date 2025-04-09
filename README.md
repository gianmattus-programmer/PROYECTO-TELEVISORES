# 🖥️ Proyecto Tienda de Televisores - Introducción a la Algoritmia 

## 📚 Curso
**Curso:** Introducción a la Algoritmia – 2025-01  
**Docente:** Gian Carlo Quiroz Guzman  
**Carrera:** Desarrollo Web  
**Ciclo:** Primero  
**Modalidad:** Virtual

## 👥 Integrantes del Grupo
| Integrante  | Funcionalidades Asignadas |
|-------------|----------------------------|
| **[Nombre del Coordinador]** | Coordinación general del proyecto |
| **Oscar**    | Archivo: Salir del sistema |
| **Giancarlos** | Mantenimiento: Consultar televisores, Modificar televisor, Listar televisores |
| **Alexis**   | Ventas: Vender televisores |
| **George**   | Configuración: Configurar descuentos, Configurar obsequios |
| **Oscar**    | Ayuda: Acerca de la Tienda |

---

## 🎯 Objetivo del Proyecto
Desarrollar una aplicación en lenguaje Java que simule el sistema de gestión de una **tienda de televisores**, permitiendo el mantenimiento de productos, gestión de ventas con descuentos y obsequios personalizados, así como la configuración flexible de promociones. Esta solución algorítmica está orientada a mejorar la eficiencia operativa de un comercio minorista electrónico.

---

## 📦 Funcionalidades del Menú Principal

### 📁 Archivo *(Oscar)*
- **Salir del programa:** Cierra la aplicación de forma segura y ordenada.

### 🔧 Mantenimiento *(Giancarlos)*
- **Consultar televisores:** Permite al usuario seleccionar un modelo de televisor y visualizar todos sus detalles de forma no editable.
- **Modificar televisor:** Permite actualizar los datos de un modelo específico mediante campos editables.
- **Listar televisores:** Muestra un reporte con todos los televisores registrados, incluyendo sus características principales.

### 🛒 Ventas *(Alexis)*
- **Vender:** Gestiona la venta de televisores permitiendo ingresar el modelo y la cantidad. Calcula el total, aplica descuentos por volumen y asigna obsequios automáticamente. Además, registra y muestra un resumen de la venta con los siguientes datos:
  - Modelo
  - Precio unitario
  - Cantidad
  - Importe total
  - Descuento aplicado
  - Total a pagar
  - Obsequio entregado

### ⚙️ Configuración *(George)*
- **Configurar descuentos:** Permite modificar los valores de los descuentos aplicados según rangos de cantidades adquiridas.
- **Configurar obsequios:** Posibilita cambiar los premios entregados según la cantidad de televisores comprados.

### ❓ Ayuda *(Oscar)*
- **Acerca de la Tienda:** Presenta información general sobre el software, la versión y los autores del proyecto.

---

## 📊 Datos Simulados
Los televisores usados en este proyecto presentan las siguientes características mínimas:
- **Modelo**
- **Marca**
- **Tamaño en pulgadas**
- **Resolución (Full HD, 4K, etc.)**
- **Tipo de pantalla (LED, OLED, QLED, etc.)**
- **Precio (en soles)**

Se simulan múltiples televisores usando variables globales como `modelo0`, `precio0`, etc., de acuerdo a las restricciones del proyecto (sin uso de arreglos).

---

## 💡 Consideraciones Técnicas
- Se utiliza **Java** como lenguaje de programación.
- Interfaces gráficas desarrolladas con **Swing**.
- Uso obligatorio de **métodos** para dividir la lógica por funciones.
- **Sin uso de arreglos ni estructuras complejas**, cumpliendo con las restricciones del curso.
- Se valida la entrada de datos en todas las interfaces.
- Se muestra un mensaje estadístico cada cinco ventas, con resumen acumulado y porcentaje de cuota diaria.

---

## ✅ Cronograma de Avances
| Semana | Entregable               | Descripción breve                                        |
|--------|---------------------------|-----------------------------------------------------------|
| 2      | Presentable 1            | Diseño completo de GUIs y estructuras de diálogo         |
| 4      | Presentable 2            | Funcionalidad al 50%, incluyendo ventas y mantenimiento  |
| 7      | Entrega final            | Proyecto funcional completo y entrega de informe final   |

---

## 📌 Requisitos Técnicos
- Lenguaje: **Java 8+**
- IDE sugerido: **Eclipse IDE 2025-03 R**
- Plataforma: **Windows 10/11**
- No se permite el uso de **arreglos ni estructuras complejas**

---
