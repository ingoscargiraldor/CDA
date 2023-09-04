# CDA
Ciencia de datos aplicada Taller1

## Para verificar los datos puede acceder al siguiente link
<a href="https://github.com/ingoscargiraldor/CDA/blob/main/airbnb/eda.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## 1. A continuación se detalla el dataset seleccionado para el analisis,
El dataset de la ciudad de Nueva York lo encontrara en la carpeta airbnb/data,

# Análisis de Datos para Inversionistas de Airbnb en New York

Este análisis se centra en proporcionar información valiosa para inversionistas interesados en el mercado inmobiliario de Airbnb en la icónica ciudad de Nueva York.

## Dataset

**Dataset Utilizado:** Airbnb NewYork

**Dimensiones del Dataset:**
- Número de filas: 43,566
- Número de columnas: 75

## 2. Entendimiento inicial de los datos, 
Podra encontrar sobre el Notebook compartido secciones de analisis univariado como:

* Analysis univariate for price
* Analysis univariate for Minimum_nights
* Analysis univariate for Neighbourhood
* Analysis univariate for room_type
* Analysis univariate for review_scores_value

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

### 5. review_scores_value (cuantitativo)
- Gran cantidad de revisiones similares.
- Valor máximo: 5, valor mínimo: 0.
- 25% de hospedajes sin reseñas, relacionado con la moda.

## 3. Estrategia de Análisis

La estrategia de análisis se centrará en proporcionar una visión detallada y fundamentada para determinar la mejor opción de inversión inmobiliaria. Comenzando con el cálculo de estadísticos básicos como media, mediana y desviación estándar para datos cuantitativos, para datos categóricos se trabajará con frecuencia relativa, valores únicos y gráficas, se buscará comprender la distribución y dispersión de los precios de las propiedades. Además, se calcularán percentiles para identificar valores atípicos que podrían afectar la toma de decisiones. Para una perspectiva más completa, se emplearán técnicas gráficas como histogramas y bar plots para visualizar la distribución de precios y detectar patrones en función de atributos como los vencindarios y la evaluación de reseñas.

Asimismo, se llevará a cabo un análisis de correlación para examinar las relaciones entre los precios de las propiedades y otros atributos relevantes, como el valor de las reseñas o el tipo de habitaciones disponibles. Se utilizará un mapa de calor para representar gráficamente las correlaciones disponibilidad y resaltar las características que influyen significativamente en el precio al final del analisis. Ademas se presentara unos diagramas de cajas con analisis multivariado teniendo presente las reseñas con calificación de 4 o superior, estas nos ayudaran a tomar y presentar las conclusiones finales para realizar recomendaciones a los inversionistas de donde, como ofertar y la felxibilidad de ofrecer los hospedajes por la plataforma de airbnb.


## 4. Desarrollo de la Estrategia

En el subtitulo de Final phase of decision making se presentan los graficos de cajas en los cuales se basaron la mayor parte de recomendaciones, sin embargo, es preciso afirmar que todo el analisis univariado, bicariado y multivariado realizan en conjunto un gran peso en la toma de decisiones y finalmente redactar el informe ejecutivo con las recomendaciones.

## 5. Generación de resultados:

A continuación, se presentarán las recomendaciones a nivel de estrategia para adquirir un apartamento y que genere rentabilidad para operarlo bajo la aplicación de Airbnb en la ciudad de New York.

Los datos en los cuales se basan las conclusiones son los siguientes: Precio, noches mínimas, vecindario, puntaje en las reseñas y tipo de hospedaje, y estos han sido trabajados en estrategias como análisis univariado, bivariado y multivariado.

Conclusiones:

- Reseñas y Precios: Nuestro análisis ha revelado que, independientemente del precio, los huéspedes tienden a calificar positivamente propiedades con precios tanto bajos como altos. Esto sugiere que es posible ser flexible con los precios y aún así obtener altas tasas de satisfacción de los huéspedes.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/00eaad97-4b76-4f21-8c21-32f2d6c79bd9)

- Elección del Vecindario: Basándonos en el análisis de datos, Bedford-Stuyvesant y Williamsburg destacan como los vecindarios más prometedores para invertir. Estas áreas no solo mantienen calificaciones altas, sino que también ofrecen flexibilidad en los precios, lo que permite mantener precios atractivos para los huéspedes.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/17c542ae-0854-48e6-a3a0-b24190c70799)

- Tipo de Hospedaje: Las propiedades completas o casas enteras son la opción preferida. Estos alojamientos tienden a ser los más solicitados y generan reseñas positivas. Además, ofrecen flexibilidad en la fijación de precios, lo que puede aumentar la rentabilidad.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/dbf5298d-eb05-4d5c-8e2b-6438aaa74290)

- Vecindario Williamsburg: Williamsburg se destaca como una opción atractiva para inversión. Ofrece una alta demanda, precios flexibles y calificaciones sobresalientes. Es una zona en crecimiento que merece consideración.
![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/28d48ea7-a3c6-4e06-a3b3-77b830d036c1)

- Noches Mínimas: La mayoría de las propiedades exitosas tienen un requisito de noches mínimas de 1 a menos de 100. La mayor frecuencia de solicitud se encuentra en estancias de 30 días. Por lo tanto, recomendamos establecer noches mínimas flexibles para atraer a una variedad de huéspedes.

![image](https://github.com/ingoscargiraldor/CDA/assets/99930749/bd4f8d8f-a21a-46b5-8916-2ecf4da38a76)

# Recomendaciones
En base a estas conclusiones, recomendamos invertir en propiedades ubicadas en Bedford-Stuyvesant y Williamsburg, preferiblemente casas o apartamentos completos. Mantener altas calificaciones de reseñas es esencial, y ser flexible con los precios puede atraer a un público diverso. Los precios pueden variar desde los 30 USD hasta los 400 USD, aunque el precio que más llama la atención es de 150 USD. Además, considere una política de noches mínimas que abarque desde 1 noche hasta menos de 100, para satisfacer las necesidades de diferentes huéspedes.

---
