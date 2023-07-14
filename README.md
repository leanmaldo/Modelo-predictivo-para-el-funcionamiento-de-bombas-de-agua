# NTT_DATA_Retos
Retos de la Escuela de Talento Digital de NTT DATA Foundation para obtener la certificación "Python Data Analyst"
# EXTRACCION DE AGUA EN TANZANIA
# PLANTEAMIENTO DEL PROBLEMA 
Tanzania se enfrenta a inmensos problemas relacionados con sus sistemas de agua y saneamiento. Casi el 43% de la población carece de acceso al agua potable básica, y sólo un 25% utiliza un saneamiento gestionado de forma segura. Más del 70% de las catástrofes naturales del país están relacionadas con el cambio climático y vinculadas a las sequías recurrentes, así como a las inundaciones, que han provocado el colapso de las infraestructuras de suministro de agua y saneamiento. A esto se le suma, que el país gasta el 70% del presupuesto sanitario en enfermedades prevenibles, relacionadas con el agua, el saneamiento y la higiene. 
Para lograr que las personas de Tanzania tengan un suministro de agua potable sustentable en el tiempo, es necesario conocer el estado de las bombas de extracción del agua, con el fin de poder mantener su buen funcionamiento o corregir cualquier inconveniente lo más rápido posible. 

# SOLUCION RECOMENDADA
Podemos afirmar entonces, que el objetivo final del proyecto es determinar si las bombas de agua son funcionales o no. Para poder alcanzar dicho objetivo se optó por desarrollar un modelo predictivo, que permita precisamente predecir con la mayor exactitud posible, si una bomba es funcional o no, utilizando un conjunto de variables relacionadas con los pozos y su entorno. Para llevar a cabo la solución planteada, se debieron desarrollar diferentes fases del proyecto:
# Recopilación de datos:
Se recopilaron datos relacionados con las características de los pozos de agua, como la carga estática total, la altitud, las coordenadas GPS, el nombre del punto de agua, la cuenca hidrográfica, la localización geográfica, la población, etc.
También se recopilaron datos sobre aspectos operativos de los pozos, como el financiamiento, la organización responsable de la instalación, la gestión del pozo, el tipo de extracción de agua, el costo del agua, la calidad del agua, etc.
Fue necesario profundizar en el conocimiento y entendimiento del problema en cuestión, que en este caso era la falta de certeza para saber si una bomba de agua era funcional o no. A su vez, no nos quedamos únicamente con la información brindada, sino que realizamos una búsqueda paralela, para saber qué información relevante, y que no estuviera en la información ya analizada, nos podría ayudar a encontrar la mejor solución. 

# Construcción de base de datos:
Como los datos se obtuvieron de diversas fuentes, se procedió a crear una base de datos sólida que almacenara todos los datos recopilados, asegurando su integridad y accesibilidad. 
Al momento de recopilar los datos, los mismos se encontraban inconexos entre sí, es decir que eran datos aislados. Para resolver este problema, se construyó un Diagrama ER, el cual permitió gráficamente representar entidades, atributos y relaciones entre los mismos, facilitando la comprensión y visualización de cómo se organizaron los datos en la base.
Posteriormente se procedió a la construcción del modelo relacional, el cual ayudó a traducir el diagrama ER en una estructura lógica. Esto implicó definir las tablas, sus atributos y las relaciones entre ellas.  Estos dos pasos fueron muy importantes para poder crear una base de datos bien estructurada y eficiente. 
La creación de la base de datos no solo tuvo como objetivo el almacenar todos los datos en una misma fuente, sino también facilitar el análisis de la información. 

# Análisis exploratorio de datos:
Se realizó un análisis detallado de los datos recopilados para comprender su estructura, distribución y relaciones entre variables. A partir de dicho análisis, se identificaron valores faltantes, valores atípicos y posibles errores en los datos, y se tomaron medidas para abordar estos problemas.
Se examinaron las distribuciones de las variables y se realizaron transformaciones en los casos necesarios. A su vez, se llevaron a cabo análisis estadísticos y visuales para obtener información sobre las características y patrones de los datos.

- Preprocesamiento de datos:
Se realizaron pasos de limpieza de datos para tratar los valores faltantes, los valores atípicos y los errores identificados durante el análisis exploratorio.
Se llevaron a cabo codificaciones y transformaciones de variables, como la codificación de variables categóricas y la estandarización de variables numéricas.
Se dividió el conjunto de datos en conjuntos de entrenamiento y prueba para su posterior modelado y evaluación.

- Modelado y evaluación:
Se aplicaron técnicas de selección de características para identificar las variables más relevantes para la predicción.
Se utilizó una variedad de algoritmos de clasificación, como árboles de decisión, regresión logística, SVM, Random Forest, etc.
Los modelos se entrenaron utilizando el conjunto de entrenamiento y se evaluaron utilizando el conjunto de prueba.
Se utilizaron métricas de evaluación, como precisión, recall, F1-score y matriz de confusión, para medir el rendimiento de los modelos.

- Optimización y ajuste de hiperparámetros:
Se realizaron técnicas de optimización de hiperparámetros para ajustar los modelos y mejorar su rendimiento.

- Validación y comparación de modelos:
Se utilizaron técnicas de validación cruzada para evaluar la capacidad de generalización de los modelos.
Se compararon y seleccionaron los modelos que mostraron el mejor rendimiento según las métricas de evaluación establecidas.
Se realizaron pruebas adicionales para verificar la robustez y la estabilidad de los modelos seleccionados.

- Implementación y despliegue:
Se implementó el modelo seleccionado en un entorno de producción para su uso práctico.
Se realizaron pruebas exhaustivas para garantizar que el modelo implementado funcione correctamente y produzca resultados precisos y confiables.

# Visualización de resultados obtenidos:
Una vez puesto en funcionamiento el modelo, se procedió a la realización de un cuadro de mando, con el objetivo de poder visualizar la situación en tiempo real. El contar con información precisa y actualizada obtenida a partir de indicadores de rendimiento, nos permite actuar de forma ágil ante incidencias, facilitando el análisis y la toma de decisiones. 

# VALOR DE LA SOLUCION 
Al conocer con mayor rapidez y precisión el estado de las bombas de extracción de agua, se pretende poder reducir los tiempos de inactividad de las mismas, lo que traería aparejado una mayor cantidad de agua potable en circulación apta para el consumo de las distintas poblaciones de Tanzania, disminuyendo considerablemente la posibilidad de contraer enfermedades prevenibles, y permitiendo utilizar el presupuesto sanitario para otras circunstancias. 
