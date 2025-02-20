# Proyecto-P1
Lo datos para trabajar se recuperaron de La Organización Mundial de la Salud (OMS), a través de su Observatorio Mundial de la Salud (GHO), se recopiló y monitoreo información sobre el estado de salud y otros factores asociados en todos los países. Sus conjuntos de datos están disponibles públicamente para el análisis de información relacionada con la salud. Para recopilar los datos se utilizó un conjunto de datos sobre la esperanza de vida y factores de salud de 193 países, obtenido del repositorio de la OMS, complementado con datos económicos extraídos del sitio web de las Naciones Unidas.

Se seleccionaron únicamente aquellos factores críticos más representativos dentro de las categorías de salud. Durante los últimos 15 años, se ha observado avance en el sector sanitario importante, lo que ha mejorado las tasas de mortalidad, especialmente en los países en desarrollo, en comparación con las tres décadas anteriores. Por ello, el análisis se centra en el período 2000-2015 para 193 países. Los distintos archivos de datos fueron combinados en un único conjunto para facilitar el análisis.

Respecto al tratamiento de los datos previo a este proyecto, una inspección visual inicial reveló la presencia de valores faltantes. Dado que los datos provenían de la OMS, no se detectaron errores evidentes. Para el tratamiento de los valores ausentes, se utilizó el software R con la función Missmap, que evidenció que la mayoría de los datos ausentes correspondían a población, hepatitis B y PIB. Estos valores faltantes se concentraban en países menos conocidos, como Vanuatu, Tonga, Togo y Cabo Verde, lo que dificultó la recopilación completa de la información. Por ello, se decidió excluir estos países del conjunto de datos final.

El archivo consolidado contiene 22 columnas y 2938 filas, lo que representa un total de 20 variables predictoras. Estas variables se agruparon en cuatro grandes categorías: factores relacionados con la inmunización, factores de mortalidad, factores económicos y factores sociales.

En el proyecto que se desarrollará a continuación se buscará identificar si, a partir de información relacionada con factores de salud y economía, es posible predecir la esperanza de vida de una población. Además, caracterizar la relación entre la tasa de mortalidad adulta y la esperanza de vida, analizando su impacto en diferentes países y periodos de tiempo.

Índice:

[Vista Previa](./P P1 598303.html)

[Codigo.jpynb](./P P1 598303.ipynb)

[Base de Datos](./Life_Expectancy_Data.xls)
