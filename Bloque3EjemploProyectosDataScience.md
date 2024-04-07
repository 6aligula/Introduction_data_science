El índice del documento "Bloque 3: Ejemplos de proyectos en el ámbito de la ciencia de datos" es el siguiente:

Introducción
Índice
## 3 Proyectos de ciencia de datos para el desarrollo y la acción humanitaria
    3.1. La deducción de los desplazamientos diarios de los habitantes de Yakarta a partir de los datos de Twitter
        3.1.1. La recogida de datos
        3.1.2. El análisis de los desplazamientos
    3.2. El uso de los datos masivos para estudiar los patrones de rescate en el mar Mediterráneo
    3.3. Twitter y la implicación global sobre el cambio climático

## 4 Ciencia de datos para el control de epidemias. El caso del Ébola
    4.1. El caso del Ébola
    4.2. Metodología
    4.3. Resultados

## 5 El análisis y la visualización de los recorridos de los taxis de Nueva York
    5.1. Datos
    5.2. El análisis de la información
        5.2.1. Variables categóricas
        5.2.2. Variables numéricas
        5.2.3. Variables geográficas
    5.3. La creación de un modelo
    5.4. La obtención de conocimiento
Resumen
Bibliografía​​.

```bash
del punto 3.1.1 y 3.1.2 puedes extraer toda la informacion mas relevante, incluye todos los mensajes importantes
```

# 3.1.1. La recogida de datos

En Yakarta, se buscó aprovechar la geolocalización de los mensajes de Twitter para mapear los patrones de desplazamiento en su área metropolitana, utilizando la alta actividad en esta red social de sus habitantes.
Se recopilaron millones de tuits con datos de GPS, analizando las relaciones entre los principales distritos del área metropolitana.
Se enfrentó el desafío de que Twitter podría no ser una representación fiel de la población debido al acceso desigual a la red social entre diferentes grupos de la población, por lo que se calibraron los resultados ponderándolos según la población total de cada distrito​​.

# 3.1.2. El análisis de los desplazamientos

Se recolectaron datos de aproximadamente 1.5 millones de usuarios, obteniendo información detallada de más de 300,000 usuarios únicos tras la calibración.
Para cada usuario, se estableció el origen (donde más mensajes se escriben entre las 9 de la noche y las 7 de la mañana) y el destino (lugar de mayor actividad durante el día laboral, excluyendo el origen).
La metodología permitió dibujar los movimientos entre los diez distritos principales, ofreciendo una alternativa rápida y eficaz en comparación con las encuestas tradicionales.
Los resultados obtenidos mostraron una similitud sorprendente con los datos de una encuesta oficial, aunque se obtuvieron de manera mucho más rápida y posiblemente con un grado de precisión más realista. Esta comparativa reveló la potencialidad de utilizar Twitter como una herramienta para monitorear los desplazamientos diarios en tiempo real y con un bajo costo​​.
Estos puntos resaltan la innovación en la recopilación y análisis de grandes volúmenes de datos de redes sociales para abordar problemas complejos de urbanismo y movilidad, demostrando la aplicabilidad práctica de la ciencia de datos en contextos urbanos densamente poblados.

```bash
del punto 3.2 y 3.3 puedes extraer toda la informacion mas relevante, incluye todos los mensajes importantes
```
# 3.2. El uso de los datos masivos para estudiar los patrones de rescate en el mar Mediterráneo

Este proyecto se inició en respuesta al incremento de muertes de migrantes en el mar Mediterráneo durante 2016. Utilizó datos de localización de barcos (AIS) para entender los patrones de rescate.
Los científicos analizaron los movimientos y velocidades de los barcos para identificar operaciones de rescate, utilizando esta información para visualizar las rutas y acciones de rescate en el mar.
Se descubrió que las llamadas de socorro se hacían cada vez más cerca de la costa de Libia, lo que significaba que los rescates tenían que realizarse en áreas más amplias y peligrosas, aumentando el riesgo de muertes.
Este análisis permitió a las ONG y organismos de rescate mejorar la planificación y ejecución de sus operaciones de rescate en el Mediterráneo​​.

# 3.3. Twitter y la implicación global sobre el cambio climático

Este análisis se enfocó en el uso de Twitter para medir el interés y la implicación global en temas relacionados con el cambio climático antes, durante y después de la cumbre del clima de 2014.
Se buscaba entender cómo las conversaciones en Twitter reflejaban el interés y las opiniones públicas sobre el cambio climático, analizando el volumen y contenido de los tuits relacionados.
Se utilizó análisis de lenguaje natural para categorizar los tuits en diferentes temas relacionados con el cambio climático y se analizó el sentimiento de los mensajes.
Los resultados mostraron un aumento significativo en la actividad de Twitter durante la cumbre, así como un aumento en las conversaciones relacionadas con el cambio climático en los meses posteriores.
Se identificó que temas como la política y la economía eran predominantes en la conversación, lo que indica posibles enfoques para campañas de sensibilización y activismo.
Este proyecto ilustra el potencial de las redes sociales como herramientas para medir en tiempo real la percepción y el interés del público en importantes cuestiones globales como el cambio climático​​.

Estos puntos subrayan la capacidad de la ciencia de datos para aprovechar grandes volúmenes de información digital en la mejora de la respuesta humanitaria y la comprensión de la percepción pública sobre temas críticos globales, respectivamente.

```bash
del punto 4.1, 4.2 y 4.3  puedes extraer toda la informacion mas relevante, incluye todos los mensajes importantes
```

# 4.1. El caso del Ébola

La expansión del virus del Ébola en 2014 en África Occidental fue un reto significativo, con miles de muertes en Liberia, Guinea, y Sierra Leona. La ITU (Unión Internacional de Telecomunicaciones) lanzó la aplicación móvil Ebola-Info-Sharing para facilitar la distribución de información oficial y mejorar la comunicación en terreno.
El análisis de los datos de llamadas (CDR, Call Detail Record) fue crucial para entender los movimientos humanos y prever la propagación del Ébola, facilitando la implementación de medidas preventivas y estrategias de contención​​.

# 4.2. Metodología

Para el análisis se utilizaron los CDR, que reflejan los movimientos y estancias de las personas, obtenidos de operadores móviles. Estos datos fueron anonimizados y analizados para mapear los desplazamientos desde zonas afectadas hacia otras regiones.
La metodología incluyó la eliminación de datos personales, la triangulación para mejorar la precisión de las ubicaciones, y la interpolación de rutas para identificar los movimientos más probables de las personas. Finalmente, se agregaron los resultados en una base de datos espacial para su análisis y visualización​​.

# 4.3. Resultados

La interpretación de los CDR proporcionó información valiosa sobre cómo y dónde se movían las personas en relación con las zonas afectadas por el Ébola, permitiendo identificar potenciales nuevos brotes.
Se reveló, por ejemplo, que las llamadas de emergencia relacionadas con el Ébola se hacían cada vez más cerca de la costa de Libia, aumentando el riesgo de propagación de la enfermedad.
Estos datos ayudaron a las autoridades y organizaciones sanitarias a mejorar las estrategias de intervención, proporcionando un mapa más claro de la movilidad humana en el contexto de la epidemia del Ébola​​.

```bash
del punto 5.1  puedes extraer toda la informacion mas relevante, incluye todos los mensajes importantes
```
# 5.1 El análisis y la visualización de los recorridos de los taxis de Nueva York"

Origen de los Datos: Se utilizó un conjunto de datos detallado que contiene todos los viajes realizados por taxis en Nueva York durante el año 2013. Esta información fue obtenida mediante una petición basada en una ley del estado de Nueva York que permite acceder a ciertos datos bajo condiciones específicas​​.

Características del Conjunto de Datos: El conjunto de datos es considerablemente grande, ocupando más de 19 GB y dividido en varios archivos CSV, con aproximadamente 14 millones de registros por archivo. Esto subraya tanto la riqueza de la información disponible como los desafíos relacionados con su manejo y análisis debido al volumen de los datos​​.

Contenido del Conjunto de Datos: Incluye información detallada sobre cada viaje, como el punto de recogida y destino (con coordenadas de latitud y longitud), tiempo del trayecto, distancia recorrida, y el coste del viaje. Esto ofrece una visión exhaustiva de la movilidad urbana dentro de la ciudad, proporcionando una base sólida para análisis posteriores​​.

Desafíos en la Calidad de los Datos: El conjunto de datos contiene registros incompletos, errores, y columnas que podrían no ser relevantes para todos los análisis, como las identificaciones de las licencias de taxi. La presencia de estos desafíos enfatiza la importancia del preprocesamiento y la limpieza de datos como pasos preliminares esenciales para cualquier análisis de ciencia de datos​​.

Esta sección resalta la complejidad y el potencial de los grandes conjuntos de datos en el análisis urbano y de movilidad, demostrando cómo pueden utilizarse para obtener insights sobre patrones de movilidad, comportamientos de los consumidores, y otras dinámicas urbanas. La base de datos de los taxis de Nueva York sirve como un ejemplo destacado de cómo los datos recopilados en el curso de las operaciones comerciales normales pueden proporcionar una ventana invaluable a la vida de la ciudad.

```bash
del punto 5.2, 5.2.1, 5.2.2 y 5.2.3  puedes extraer toda la informacion mas relevante, incluye todos los mensajes importantes
```
# 5.2. El análisis de la información

El primer paso es entender qué datos están disponibles en el conjunto de datos de los viajes de taxi. Esta fase implica la visualización y el análisis preliminar para comprender mejor la naturaleza de los datos, incluyendo la distribución de variables categóricas y numéricas, y la interpretación de variables geográficas a través de la visualización en mapas​​.

# 5.2.1. Variables categóricas

Proveedor del Sistema: Se observó una distribución equitativa entre dos proveedores de servicios (CMT y VTS), lo que indica una diversidad en la fuente de los datos.
Zonas Tarifarias: La mayoría de los viajes se concentraron en la zona 1, presumiblemente Manhattan, lo que refleja una mayor densidad de uso de taxis en esta área.
Método de Pago: Los métodos de pago más comunes fueron la tarjeta de crédito (CRD) y el efectivo (CSH), con algunos datos desconocidos (UNK), resaltando la importancia de la limpieza de datos​​.

# 5.2.2. Variables numéricas

Distancias Recorridas: La mayoría de los trayectos en taxi fueron cortos, alrededor de un kilómetro, aunque hubo una variabilidad significativa.
Duración del Viaje: Los tiempos de viaje más comunes rondaron los 10 minutos, sugiriendo que los taxis son usados frecuentemente para viajes rápidos por la ciudad.
Propinas: La distribución de las propinas mostró que las cantidades más comunes estaban entre uno y dos dólares, con una correlación entre el tiempo de viaje y el monto de la propina, lo que indica posibles patrones de comportamiento del consumidor​​.

# 5.2.3. Variables geográficas

La visualización de las coordenadas geográficas de los puntos de recogida y destino permitió identificar patrones espaciales claros de actividad de taxi en Nueva York, destacando áreas de alta densidad de uso y potenciales rutas populares.
Los mapas generados a partir de estas variables no solo revelaron la geografía física de la ciudad sino también patrones de comportamiento humano, como preferencias de transporte y concentración de actividades en ciertas áreas​​.
Esta sección del análisis muestra cómo el manejo y la interpretación adecuados de diferentes tipos de datos pueden ofrecer insights valiosos sobre la movilidad urbana y las dinámicas de transporte en una metrópolis como Nueva York. Los patrones descubiertos a través de la distribución de las variables categóricas, numéricas, y geográficas ofrecen una base para análisis más profundos y la modelación predictiva.

```bash
del punto 5.3 y 5.4  puedes extraer toda la informacion mas relevante, incluye todos los mensajes importantes
```
### 5.3. La creación de un modelo

- **Objetivo del Modelo**: El interés se centró en predecir la propina que un taxista puede esperar recibir, basándose en los datos disponibles de los viajes en taxi.
- **Descubrimiento de Anomalías**: Se identificó que la forma de pago era un predictor dominante en la propina recibida, destacando un patrón inesperado: la mayoría de las propinas solo se registraban cuando el pago se realizaba con tarjeta. Esto sugirió que las propinas en efectivo raramente se registraban, lo que podría indicar un sesgo en los datos reportados.
- **Construcción del Modelo**: Se procedió a construir un modelo de clasificación, inicialmente mediante regresión logística, que luego se complementó con un enfoque más sofisticado usando bosques aleatorios (Random Forest) para mejorar la predicción de las propinas.
- **Resultados del Modelo**: El modelo de bosque aleatorio mejoró significativamente la precisión de las predicciones sobre la regresión logística, lo que indica que la complejidad adicional del modelo permitió capturar mejor las relaciones entre las variables【10†source】.

### 5.4. La obtención de conocimiento

- **Insights Geográficos**: El análisis reveló que la localización (origen y destino del viaje) era un factor crucial para predecir la propina. Específicamente, se observó que los viajes que terminaban en ciertas áreas de la ciudad tendían a resultar en mayores propinas.
- **Patrones de Propina**: Los viajes con destino en las zonas periféricas de la ciudad mostraron una mayor probabilidad de recibir propinas, mientras que aquellos con destino en el centro de la ciudad (especialmente áreas turísticas y comerciales densamente pobladas) mostraban una probabilidad menor.
- **Implicaciones Prácticas**: Este conocimiento puede ser invaluable para los taxistas al planificar sus rutas y elegir ubicaciones de recogida y destino. Además, revela cómo el comportamiento de propinas puede estar influenciado por factores culturales y económicos relacionados con las áreas específicas de la ciudad【10†source】.

La sección 5.3 demuestra la importancia de adaptar el modelo a las peculiaridades de los datos disponibles, mientras que la sección 5.4 subraya cómo los modelos predictivos pueden ofrecer insights accionables no solo para entender mejor el fenómeno en estudio, sino también para aplicar este conocimiento en decisiones prácticas y operativas.