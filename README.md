# Evaluación Final 

Este repositorio contiene la evaluación final de uno de los módulos realizados en el bootcamp de Adalab. 

Podemos encontrar diferentes archivos:

Un par de **csv** con información sobre los clientes, de una compañía aérea canadiense, en relación a sus reservas, tarjetas de fidelidad, etc. Aquí hemos recogido un listado descriptivo de los datos que vamos a encontrar:
- *Loyalty Number*: Número de lealtad, posiblemente un identificador único para cada cliente.
- *Country*: País del cliente.
- *Province*: Provincia o estado del cliente.
- *City*: Ciudad del cliente.
- *Postal Code*: Código postal del cliente.
- *Gender*: Género del cliente.
- *Education*: Nivel educativo del cliente.
- *Salary*: Salario del cliente.
- *Marital Status*: Estado civil del cliente.
- *Loyalty Card*: Tarjeta de lealtad, indica si el cliente tiene una tarjeta de lealtad.
- *CLV (Customer Lifetime Value)*: Valor del cliente a lo largo del tiempo, una métrica que representa el valor total que un cliente aporta a lo largo de su relación con la empresa.
- *Enrollment Type*: Tipo de inscripción o registro del cliente.
- *Enrollment Year*: Año de inscripción del cliente.
- *Enrollment Month*: Mes de inscripción del cliente.
- *Cancellation Year*: Año de cancelación (si aplica).
- *Cancellation Month*: Mes de cancelación (si aplica).
- *Year*: Año de la transacción o registro.
- *Month*: Mes de la transacción o registro.
- *Flights Booked*: Número de vuelos reservados.
- *Flights with Companions*: Número de vuelos con acompañantes.
- *Total Flights*: Número total de vuelos.
- *Distance*: Distancia total de vuelos.
- *Points Accumulated*: Puntos acumulados por el cliente.
- *Points Redeemed*: Puntos canjeados por el cliente.
- *Dollar Cost Points Redeemed*: Costo en dólares de los puntos canjeados por el cliente.


Y, también encontramos, un **notebook de jupyter** que da respuesta a los siguientes ejercicios:

## Fase 1: Exploración y Limpieza
1. **Exploración Inicial:**
- Realiza una exploración inicial de los datos para identificar posibles problemas, como valores nulos, atípicos o datos faltantes en las columnas relevantes.
- Utiliza funciones de Pandas para obtener información sobre la estructura de los datos, la presencia de valores nulos y estadísticas básicas de las columnas involucradas.
- Une los dos conjuntos de datos de la forma más eficiente.
2. Limpieza de Datos:
- Elimina o trata los valores nulos, si los hay, en las columnas clave para asegurar que los datos estén completos.
- Verifica la consistencia y corrección de los datos para asegurarte de que los datos se presenten de forma coherente.
- Realiza cualquier ajuste o conversión necesaria en las columnas (por ejemplo, cambiar tipos de datos) para garantizar la adecuación de los datos para el análisis estadístico.
## Fase 2: Visualización
- Usando las herramientas de visualización que has aprendido durante este módulo, contesta a las siguientes gráficas usando la mejor gráfica que consideres:
    1. ¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?
    2. ¿Existe una relación entre la distancia de los vuelos y los puntos acumulados por los clientes?
    3. ¿Cuál es la distribución de los clientes por provincia o estado?
    4. ¿Cómo se compara el salario promedio entre los diferentes niveles educativos de los clientes?
    5. ¿Cuál es la proporción de clientes con diferentes tipos de tarjetas de fidelidad?
    6. ¿Cómo se distribuyen los clientes según su estado civil y género?
## Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo
**Objetivo del Ejercicio:** Utilizando un conjunto de datos que hemos compartido, se busca evaluar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes. Para ello, los pasos que deberas seguir son:
1. Preparación de Datos:
- Filtra el conjunto de datos para incluir únicamente las columnas relevantes: 'Flights Booked' y 'Education'.
2. Análisis Descriptivo:
- Agrupa los datos por nivel educativo y calcula estadísticas descriptivas básicas (como el promedio, la desviación estandar, los percentiles) del número de vuelos reservados para cada grupo.
3. Prueba Estadística:
- Realiza una prueba de A/B testing para determinar si existe una diferencia significativa en el número de vuelos reservados entre los diferentes niveles educativos.