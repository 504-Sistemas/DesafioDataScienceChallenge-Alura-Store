# 🛒 Alura Store: Análisis de Optimización de Portafolio

## 🎯 Propósito del Proyecto
El Sr. Juan enfrenta una decisión estratégica: **¿Cuál de sus cuatro tiendas debe vender para financiar su nuevo emprendimiento?**

Este proyecto utiliza análisis de datos para evaluar la eficiencia comercial, la satisfacción del cliente y el rendimiento logístico de las sucursales de Alura Store, proporcionando una recomendación basada estrictamente en métricas de desempeño (**Data-Driven**).

---

## 🛠️ Estructura del Análisis
El flujo de trabajo está diseñado de forma modular para garantizar la reproducibilidad:

* **Ingesta de Datos:** Importación automatizada de archivos CSV desde fuentes remotas.
* **ETL & Consolidación:** Limpieza y unión de datos en un DataFrame maestro (`tienda_maestra`).
* **Análisis de KPIs:**
    * **Financiero:** Ingresos totales por sede.
    * **Comercial:** Volumen de ventas por categoría y rotación de inventario.
    * **Calidad:** Promedio de satisfacción del cliente.
    * **Logística:** Análisis de costos de envío y tiempos de entrega.
* **Visualización:** Generación de un dashboard comparativo.

---

## 📈 Insights Clave
Tras el análisis exhaustivo, se identificaron los siguientes puntos críticos:

| Métrica | Líder | Hallazgo Relevante |
| :--- | :--- | :--- |
| **Facturación** | Tienda 1 | Lidera con ~ **$1,150M COP**. |
| **Satisfacción** | Tienda 3 | Mayor calificación promedio, indicando fidelidad del cliente. |
| **Logística** | Tienda 4 | Costos de envío más bajos, pero con bajo impacto en conversión. |

### Visualizaciones Incluidas
* 📊 **Gráfico de Barras:** Comparativa de ingresos totales.
* 📦 **Segmentación:** Ventas por categoría de producto.
* ⚖️ **Scatter Plot:** Relación entre Calidad (Rating) vs. Costos Logísticos.

---

## 🚀 Instrucciones de Uso

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/504-Sistemas/DesafioDataScienceChallenge-Alura-Store.git](https://github.com/504-Sistemas/DesafioDataScienceChallenge-Alura-Store.git)
    ```

2.  **Instalar dependencias:**
    Asegúrate de tener instaladas las librerías necesarias:
    ```bash
    pip install pandas matplotlib seaborn
    ```

3.  **Ejecución:**
    Abre el archivo `.ipynb` en **Google Colab** o **Jupyter Notebook** y selecciona **"Ejecutar todas las celdas"**.

---

## 💡 Recomendación Final

> **Decisión:** Se recomienda la venta de la **Tienda 4**.
>
> **Justificación:** A pesar de tener costos logísticos competitivos, presenta los ingresos totales más bajos y una rotación de productos significativamente menor. Es el activo con menor retorno de inversión (ROI) dentro del portafolio actual.
