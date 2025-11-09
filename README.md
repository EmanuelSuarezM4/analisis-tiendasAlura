# Proyecto de Análisis de Tiendas — Alura Store

## Propósito del Análisis
El propósito de este proyecto es ayudar al **Sr. Juan**, propietario de la cadena **Alura Store**, a decidir **qué tienda vender** basándose en un análisis de datos de ventas, reseñas y costos logísticos.  

Se utilizaron datos de **cuatro tiendas diferentes** para identificar cuál presenta el **menor desempeño general**, considerando factores como ingresos totales, categorías más vendidas, calificaciones de clientes y costos de envío promedio.

---

## Estructura del Proyecto

El proyecto está organizado en el notebook principal **`AluraStoreLatam.ipynb`**, el cual contiene las siguientes secciones:

1. **Extracción de Datos:**  
   Carga de los archivos CSV de cada tienda (`store1.csv`, `store2.csv`, `store3.csv`, `store4.csv`) utilizando la biblioteca Pandas.

2. **Exploración del Conjunto de Datos (EDA):**  
   Revisión de la estructura, columnas y primeras observaciones para entender la información disponible.

3. **Análisis de Indicadores:**  
   - Cálculo del ingreso total por tienda.  
   - Conteo de ventas por categoría.  
   - Promedio de valoraciones de clientes.  
   - Identificación de productos más y menos vendidos.  
   - Cálculo del costo de envío promedio.

4. **Visualizaciones:**  
   Se generaron gráficos utilizando Matplotlib para representar los resultados.

5. **Informe Final:**  
   Síntesis de resultados y recomendación final sobre qué tienda vender.

6. **(Opcional) Análisis Geográfico:**  
   Representación de las ventas en función de las coordenadas (`lat`, `lon`) con gráficos de dispersión o mapas de calor.

---

## Ejemplos de Gráficos e Insights

A continuación, algunos ejemplos de las visualizaciones generadas:

- **Gráfico de líneas:** Ingreso total comparado entre tiendas.  
- **Gráfico de dispersión:** Valoraciones promedio de los clientes.  
- **Gráfico circular:** Productos más vendidos por tienda.  
- **Gráfico de barras:** Costo de envío promedio por tienda.  

### Principales Insights:

- La **Tienda 3** presenta el mayor nivel de ingresos y cobertura geográfica.  
- La **Tienda 2** cuenta con las mejores calificaciones de satisfacción del cliente.  
- La **Tienda 4** presenta los menores ingresos y las valoraciones más bajas.  
- **Recomendación:** Vender la **Tienda 4**, ya que es la menos rentable y con menor satisfacción de clientes.

---

## Instrucciones para Ejecutar el Notebook

### Requisitos
Asegúrate de tener instalado:
- **Python 3.10+**
- **Google Colab** (o Jupyter Notebook)
- Bibliotecas necesarias:
  ```bash
  pip install pandas matplotlib folium
