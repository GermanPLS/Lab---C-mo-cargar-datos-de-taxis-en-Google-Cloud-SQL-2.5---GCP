"# Lab - C�mo cargar datos de taxis en Google Cloud SQL 2.5" 
# Cómo cargar datos de taxis en Google Cloud SQL 2.5

## Descripción general
En este lab, aprenderás a importar datos desde archivos de texto CSV a Cloud SQL y, luego, llevarás a cabo algunos análisis de datos básicos mediante consultas simples.

El conjunto de datos que se utiliza en este lab lo recopila la Comisión de Taxis y Limusinas de Nueva York y abarca los registros de todos los viajes completados en taxis amarillos y verdes en la Ciudad de Nueva York desde 2009 hasta la actualidad, así como todos los viajes en vehículos de alquiler (FHV) desde 2015 hasta la actualidad. Los registros incluyen campos que capturan la fecha y hora en que se recogieron y dejaron pasajeros, ambas ubicaciones, las distancias de los viajes, las tarifas detalladas, los tipos de tarifas, los tipos de pago y el recuento de pasajeros informado por los choferes.

Este conjunto de datos puede usarse para demostrar una amplia variedad de conceptos y técnicas sobre la ciencia de datos, y se utilizará en varios labs del programa de **Data Engineering**.

### Objetivos
Crear una instancia de Cloud SQL
Crear una base de datos de Cloud SQL
Importar datos de texto a Cloud SQL
Verificar la integridad de los datos