# CDA
Ciencia de datos aplicada Taller1

## Para verificar los datos puede acceder al siguiente link
<a href="https://github.com/ingoscargiraldor/CDA/blob/main/airbnb/eda.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

El dataset de la ciudad de Nueva York lo encontrara en la carpeta airbnb,

# Análisis de Datos para Inversionistas de Airbnb en New York

Este análisis se centra en proporcionar información valiosa para inversionistas interesados en el mercado inmobiliario de Airbnb en la icónica ciudad de Nueva York.

## Dataset

**Dataset Utilizado:** Airbnb NYC Listings and Calendar Data

**Dimensiones del Dataset:**
- Número de filas: 43,566
- Número de columnas: 75

**Tipos de Datos:**
- Cuantitativos: price, minimum_nights, maximum_nights, number_of_reviews, reviews_per_month, availability_365
- Categóricos: id, name, host_id, host_name, neighbourhood, neighbourhood_group, room_type, amenities, instant_bookable, calendar_updated

## Top 5 Atributos Clave

### 1. Precio (Cuantitativo)
- Se cuentan con 1,240 precios diferentes.
- Precio máximo: 90,120USD, precio mínimo (diferente de 0): 10USD.
- Desviación estándar alta indica una amplia variabilidad.
- La mediana me indica que la mayoria de los precipós se encuentran en un rango de hasta 136USD.
- La moda y frecuencia relativa sugieren un precio común de 150USD.

### 2. Minimum_nights (Cuantitativo)
- Hay 131 valores posibles de noches mínimas.
- Valor mínimo: 1 noche, valor máximo: 1,250 noches.
- La opción más común es de 30 días, relacionada con la moda.
- La desviación estandar me indica que hay varianza en los datos.

### 3. Neighbourhood_cleansed (Categorico)
- Se cuentan con aproximadamente 223 vecindarios limpios.
- Los barrios más populares son Bedford-Stuyvesant y Williamsburg.

### 4. Room_type (Categorico)
- Hay poca variabilidad en los tipos de habitaciones, se cuentan con 4 tipos.
- La mayoría de los personas prefieren alquilar el apartamento completo.

### 5. Number_of_reviews (Categorico)
- Gran cantidad de revisiones similares.
- Valor máximo: 2,024, valor mínimo: 0.
- 24% de hospedajes sin reseñas, relacionado con la moda.

## Estrategia de Análisis

La estrategia de análisis se centrará en proporcionar una visión detallada y fundamentada para determinar la mejor opción de inversión inmobiliaria. Comenzando con el cálculo de estadísticos básicos como media, mediana y desviación estándar para datos cuantitativos, para datos categóricos se trabajará con frecuencia relativa, valores únicos y gráficas, se buscará comprender la distribución y dispersión de los precios de las propiedades. Además, se calcularán percentiles para identificar valores atípicos que podrían afectar la toma de decisiones. Para una perspectiva más completa, se emplearán técnicas gráficas como histogramas y bar plots para visualizar la distribución de precios y detectar patrones en función de atributos como la ubicación y la cantidad de revisiones.

Asimismo, se llevará a cabo un análisis de correlación para examinar las relaciones entre los precios de las propiedades y otros atributos relevantes, como la cantidad de reseñas o el tipo de habitaciones disponibles. Se utilizará un mapa de calor para representar gráficamente las correlaciones disponibilidad y resaltar las características que influyen significativamente en el precio al final del analisis. Además, se empleará un gráfico de scatterplot para explorar la relación entre las revisiones y los precios, lo que permitirá identificar posibles tendencias y patrones.


## Desarrollo de la Estrategia

A continuación, se presentarán las recomendaciones a nivel de estrategia para adquirir un apartamento y que genere rentabilidad para operarlo bajo la aplicación de Airbnb en la ciudad de New York.
Los datos en los cuales se basan las conclusiones son los siguientes: Precio, noches mínimas, vecindario, numero de reseñas y tipo de hospedaje, y estos han sido trabajados en estrategias como análisis univariado, bivariado y multivariado.

Conclusiones:

- Se seleccionaron las mejores reseñas debido a que la tendencia de los datos nos muestra que los precios más altos tienden a tener mejores reseñas altas.

- Invertir en propiedades con mejores reseñas, ya que los precios altos tienden a tener reseñas más altas.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/5b76c745-23e9-4281-adbc-6e71e6145792)

- De acuerdo con el grafico que representan datos de reseñas superiores a 4 la mejor opción para invertir es en Bedford-Stuyvesant o Williamsburg debido a que son sectores que manejan una calificación alta y adicional los precios son flexibles, se logran mantener precios bajos, así como altos en comparación con las demás muestras.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/bf22903e-f2a8-43ca-83bf-1156d949bfd8)

- La mejor opción de inversión es sobre un apartamento completo o casa entera, esta opción me permite variar sobre los precios estándar manejados en la zona, adicional son los mas solicitados con reseñas positivas.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/c32dadda-d215-4d59-9b65-4137ff9bbf23)

- Revisando el grafico por categorías se concluye que una opción que ofrece mas flexibilidad en la asignación del valor de la renta y mantiene una frecuencia alta de asistencia con un buen puntaje de reseñas es Williamsburg.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/68f1bbca-5243-4e2c-b6e9-db145b9d9b20)

- La mejor opción de solicitud de mínimas noches se da desde 1 hasta una opción menor a 100, conociendo que la mayor frecuencia de solicitud es de 30 días.
---
