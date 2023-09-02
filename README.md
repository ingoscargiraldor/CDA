# CDA
Ciencia de datos aplicada Taller1
Aquí tienes el texto formateado en sintaxis de un archivo README:

---

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
- La mayoría de los precios se encuentran en el rango de 2,000USD a 3,500USD.
- Precio máximo: 90,120USD, precio mínimo (diferente de 0): 10USD.
- Desviación estándar alta indica una amplia variabilidad.
- La moda y frecuencia relativa sugieren un precio común de 150USD.

### 2. Minimum_nights
- Hay 131 valores posibles de noches mínimas.
- Valor mínimo: 1 noche, valor máximo: 1,250 noches.
- La opción más común es de 30 días, relacionada con la moda.

### 3. Neighbourhood_cleansed
- Los barrios más populares son Nueva York y Brooklyn.
- Se observa un alto número de valores NaN.

### 4. Room_type
- Hay poca variabilidad en los tipos de habitaciones.
- La mayoría de los hospedajes alquilan el apartamento completo.

### 5. Number_of_reviews
- Gran cantidad de revisiones similares.
- Valor máximo: 2,024, valor mínimo: 0.
- 24% de hospedajes sin reseñas, relacionado con la moda.

## Estrategia de Análisis

La estrategia de análisis se enfoca en proporcionar una visión detallada y fundamentada para determinar la mejor opción de inversión inmobiliaria en Airbnb en Nueva York. Se utilizan técnicas de análisis univariado y bivariado para comprender la distribución de precios, la relación entre atributos y la influencia en la popularidad de los anfitriones.

## Desarrollo de la Estrategia

A continuación, se presentan las recomendaciones basadas en el análisis:

- Invertir en propiedades con mejores reseñas, ya que los precios altos tienden a tener reseñas más altas.

- Sectores recomendados: Bedford-Stuyvesant y Williamsburg, con altas calificaciones y precios flexibles.

- Tipo de habitación: Apartamento completo o casa entera, altamente solicitados y con buenas reseñas.

- Mayor flexibilidad en la asignación de precios y alta asistencia en Williamsburg.

- Solicitar un mínimo de noches entre 1 y 100, con 30 días como la opción más común.

Este análisis proporciona una base sólida para la toma de decisiones de inversión en el mercado de Airbnb en Nueva York.

---
