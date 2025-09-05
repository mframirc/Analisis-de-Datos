Título del proyecto

“Pesnsiones_IPS_202412”

 Introducción: 
 
El sistema previsional chileno ha experimentado transformaciones profundas en las últimas décadas, pasando de un modelo de reparto administrado por el Estado a un sistema de capitalización individual. Sin embargo, una parte significativa de la población —especialmente adultos mayores, personas con invalidez y beneficiarios de sobrevivencia— continúa recibiendo pensiones bajo el régimen antiguo gestionado por el Instituto de Previsión Social (IPS).

Objetivo 

Este proyecto realiza un análisis exploratorio de los datos (EDA) de pensiones del sistema de reparto, con el objetivo de identificar patrones distributivos, brechas estructurales y oportunidades de mejora. Se examinan variables clave como el monto bruto de pensión (), sexo (), tipo de pensión () y región (), utilizando técnicas de visualización comparativa.

Estructura metodológica del proyecto
El análisis exploratorio de datos (EDA) realizado en Python a partir de un conjunto de datos real, se recorren las etapas fundamentales del EDA

Descripción de la base de datos: 
-Información general sobre el dataset, columnas, tipos de datos y contexto del mismo.

1.  Carga del dataset
   - Importación desde fuente original manteniendo nombres de columnas y trazabilidad.

2. Limpieza y transformacion
    - Revisión de estructura, tipos de datos y resumen estadístico, exploración inicial con
      funciones básicas (.head(), .info(), .describe()), identificación de valores faltantes, ajuste
     de tipos de variables y detección de valores atípicos.

3. Visualizaciones Exploratoria
    Conclusiones Análisis IDA – Pensiones IPS Diciembre 2024

4. Regresión lineal simple (bivariada)
   Conclusiones 1

5. Regresión multivariada
   Conclusiones 2


Conclusión Final 

A partir del análisis realizado, se concluye que el monto de pensión está influenciado por múltiples factores, y no puede explicarse de forma simple ni lineal. Si bien variables como edad e ingreso muestran cierta asociación, su impacto varía según el perfil del afiliado, lo que evidencia la necesidad de segmentar y enriquecer el modelo con dimensiones estructurales. Este ejercicio demuestra cómo el análisis multivariado permite revelar patrones ocultos, desafiar intuiciones y generar recomendaciones más precisas para la toma de decisiones previsionales.
