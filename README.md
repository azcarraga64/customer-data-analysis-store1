# 🛒 Customer Data Analysis — Store 1
**Python · Pandas · Data Cleaning · Customer Segmentation**

---

## 📌 Descripción del proyecto

Análisis de la base de datos de clientes de **Store 1**, una tienda de retail con categorías como electrónica, ropa, libros, belleza y hogar.

El objetivo fue limpiar, transformar y analizar los registros de clientes para generar insights accionables que apoyen decisiones de negocio y estrategias de marketing segmentado.

---

## 🎯 Objetivos

- Limpiar y estandarizar datos crudos de clientes (nombres, edades, categorías)
- Construir funciones reutilizables para procesamiento de datos
- Calcular ingresos totales por cliente y por categoría
- Segmentar clientes por edad y nivel de gasto
- Identificar patrones de compra por categoría de producto

---

## 🔧 Herramientas y tecnologías

| Herramienta | Uso |
|---|---|
| Python | Lenguaje principal |
| Listas y funciones | Estructuras de datos y lógica de limpieza |
| Métodos de strings | Limpieza de nombres (`strip`, `split`, `lower`) |
| Bucles y condicionales | Filtrado y segmentación de clientes |
| `sum()` | Cálculo de ingresos por cliente |

---

## 🧹 Proceso de limpieza de datos

Los datos crudos presentaban los siguientes problemas:

- ❌ Nombres con espacios en blanco y guiones bajos (`" mike_reed "`)
- ❌ Edades almacenadas como `float` en lugar de `int`
- ❌ Categorías de compra en mayúsculas (`"ELECTRONICS"`, `"SPORT"`)

**Solución aplicada:**
- Se usaron métodos `strip()`, `split()` y `lower()` para normalizar los datos
- Se creó la función `clean_user()` reutilizable para procesar cada registro
- Se aplicó la función a toda la base de datos con un bucle `for`

---

## 📊 Análisis realizados

### 1. Ingresos totales
Cálculo del total de ingresos generados por todos los clientes de la tienda.

### 2. Segmentación de clientes jóvenes
Identificación de clientes menores de 30 años para campañas de marketing dirigidas.

### 3. Clientes jóvenes con alto gasto
Filtro de clientes menores de 30 años con gasto total superior a $1,000 — candidatos para programas de beneficios especiales.

### 4. Análisis por categoría de producto
Identificación de clientes que compraron en categorías específicas (ropa, hogar, etc.) con su nombre, edad y gasto total.

### 5. Función reutilizable de segmentación
Desarrollo de la función `get_clients_by_category()` que permite filtrar clientes por cualquier categoría de forma dinámica.

---

## 💡 Resultados clave

- ✅ Base de datos de 10 clientes completamente limpia y estandarizada
- ✅ Función reutilizable para segmentar clientes por cualquier categoría
- ✅ Identificación de clientes jóvenes de alto valor para estrategias de marketing
- ✅ Estructura de datos lista para escalar a análisis más avanzados

---

## 📁 Estructura del proyecto

```
├── Proyecto2_Student_version.ipynb   # Notebook principal con análisis completo
└── README.md                         # Documentación del proyecto
```

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/azcarraga64/customer-data-analysis-store1
```

2. Abre el notebook:
```bash
jupyter notebook Proyecto2_Student_version.ipynb
```

3. Ejecuta las celdas en orden desde el inicio.

---

## 👤 Autor

**Roberto Azcárraga Olvera**  
Data Analyst | Python · SQL · Power BI  
[LinkedIn](https://linkedin.com/in/roberto-azcarraga) · [GitHub](https://github.com/azcarraga64)
