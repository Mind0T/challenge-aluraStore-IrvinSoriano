# 📊 Challenge Data Science - Alura Store Latam

## 📝 Descripción del Proyecto
Este proyecto es la solución al primer desafío de Data Science de Alura Latam. El objetivo principal es analizar el rendimiento comercial de una cadena de cuatro sucursales (Alura Store) para asesorar al Sr. Juan, el propietario, en una decisión estratégica: **¿Qué tienda debería vender para financiar un nuevo emprendimiento?**

A través de la manipulación de datos y la creación de visualizaciones, evaluamos diversas métricas clave para identificar la sucursal con el rendimiento más bajo y justificar la recomendación final.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python 3
* **Manipulación y Análisis de Datos:** `pandas`
* **Visualización de Datos:** `matplotlib`, `seaborn`
* **Entorno de Desarrollo:** Jupyter Notebook / Google Colab

## 📂 Estructura de los Datos
El análisis se nutre de 4 bases de datos en formato CSV (`tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`). Cada archivo contiene un registro detallado de las ventas, incluyendo:
* Información del producto (Nombre, Categoría, Precio).
* Logística (Costo de envío, Lugar de compra, Coordenadas).
* Métricas de satisfacción (Calificación del cliente).
* Detalles de transacción (Fecha, Vendedor, Método de pago, Cuotas).

## 📈 Análisis Realizados
El notebook documenta paso a paso la exploración de los datos, estructurada en los siguientes hitos:
1. **Análisis de facturación:** Comparativa de los ingresos totales generados por cada tienda.
2. **Ventas por categoría:** Identificación de las categorías que generan más ingresos, con foco en la tienda de menor rendimiento.
3. **Calificación promedio:** Evaluación de la satisfacción del cliente en cada sucursal (escala 1-5).
4. **Productos más y menos vendidos:** Análisis de la rotación de inventario.
5. **Envío promedio por tienda:** Comparativa de los costos logísticos asumidos en las transacciones de cada sucursal.

## 💡 Conclusión y Recomendación
Tras cruzar las métricas de volumen de ventas, ingresos, satisfacción del cliente y costos logísticos, **la recomendación analítica es vender la Tienda 4**. 

**Justificación clave:**
* Presenta la **facturación más baja** de toda la cadena, quedando más de $112 millones por debajo de la tienda líder.
* Atrae ventas con un **ticket promedio de menor valor** en comparación con las otras sucursales, a pesar de mantener un volumen de transacciones similar.
* No destaca en métricas críticas de retención como la calificación promedio frente a sus contrapartes.

## 🚀 Cómo ejecutar el proyecto
1. Clona este repositorio o descarga los archivos.
2. Asegúrate de tener instaladas las librerías necesarias: `pip install pandas matplotlib seaborn`
3. Abre el archivo `AluraStoreLatam.ipynb` en tu entorno preferido (Jupyter Notebook, JupyterLab o Google Colab).
4. Ejecuta las celdas secuencialmente para observar la transformación de los datos y las gráficas generadas.


## 👨‍💻 Autor

**Irving Soriano** Estudiante de la Licenciatura en Ciencia de Datos en ESCOM (IPN).

📫 **Contacto y Redes:**
* **LinkedIn:** [Irving Soriano](https://www.linkedin.com/in/irving-soriano)