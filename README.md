# Análisis de Comportamiento de Clientes ConnectaTel
📋 Descripción del Proyecto
Este proyecto analiza el comportamiento de uso de servicios móviles de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia. El objetivo es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas para optimizar la oferta comercial y mejorar la experiencia del usuario.

🎯 Objetivo del Proyecto
Entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes) para:

Identificar patrones de uso entre diferentes segmentos de clientes
Detectar comportamientos atípicos que puedan indicar fraude o errores
Analizar variaciones de uso según edad y tipo de plan contratado
Generar insights comerciales para diseñar mejores planes y optimizar la oferta
📊 Datasets Utilizados
El proyecto trabaja con tres fuentes principales de datos:

plans.csv: Catálogo de planes con precios, minutos incluidos, GB incluidos y costos adicionales
users_latam.csv: Información de clientes (edad, ciudad, fecha de registro, plan contratado, churn)
usage.csv: Detalle de uso real de cada cliente (llamadas con duración y mensajes con longitud)
Enlaces de descarga:
- plans.csv
- users_latam.csv
- usage.csv

🔍 Etapas del Análisis Realizadas
### 1. Exploración y Carga de Datos
- Carga de los tres datasets
- Exploración inicial de estructura y tipos de datos
- Identificación de valores faltantes y duplicados

### 2. Limpieza y Preparación de Datos
- Tratamiento de valores faltantes
- Estandarización de tipos de datos
- Detección y manejo de inconsistencias
- Validación de integridad referencial entre datasets

### 3. Integración de Datos
- Unión de las tres fuentes de datos
- Agregación del uso real por cliente
- Creación del perfil unificado de usuario

### 4. Análisis Estadístico
- Estadísticas descriptivas por segmentos
- Detección de outliers usando método IQR
- Análisis de distribuciones de uso

### 5. Segmentación de Clientes
- Creación de grupos por edad
- Segmentación por nivel de uso
- Análisis comparativo entre segmentos

### 6. Visualización y Insights
- Gráficos de distribución por segmentos
- Análisis de comportamientos atípicos
- Identificación de patrones comerciales
