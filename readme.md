# Proyecto de Análisis y Predicción de Enfermedades Cardiovasculares

## Descripción

La Organización Mundial de la Salud (OMS) estima que cada año se producen 12 millones de muertes en todo el mundo debido a enfermedades cardíacas, en su mayoría causadas por enfermedades cardiovasculares. El pronóstico temprano de estas enfermedades puede ayudar en la toma de decisiones sobre cambios en el estilo de vida para pacientes de alto riesgo y reducir complicaciones.

Este proyecto tiene como objetivo realizar análisis exploratorios y predictivos sobre un conjunto de datos de pacientes recopilado hace 10 años. A partir de estos datos, buscaremos desarrollar modelos predictivos para identificar posibles factores de riesgo y contribuir en el pronóstico de enfermedades cardiovasculares.

## Descripción del Dataset (`cardio.csv`)

La base de datos contiene varias variables con información médica y demográfica de los pacientes. A continuación, se describen las variables principales:

- `Sex`: Género del paciente (`M` para masculino, `F` para femenino).
- `Age`: Edad del paciente.
- `Education`: Nivel educativo del paciente, donde valores más altos indican un nivel educativo mayor.
- `currentSmoker`: Indica si el paciente es fumador actual (0: No, 1: Sí).
- `cigsPerDay`: Número promedio de cigarrillos fumados por día.
- `BPMeds`: Indica si el paciente toma medicamentos para la presión arterial (0: No, 1: Sí).
- `prevalentStroke`: Indica si el paciente ha tenido un accidente cerebrovascular previamente (0: No, 1: Sí).
- `prevalentHyp`: Indica si el paciente tiene hipertensión (0: No, 1: Sí).
- `diabetes`: Indica si el paciente tiene diabetes (0: No, 1: Sí).
- `totChol`: Nivel de colesterol total.
- `sysBP`: Presión arterial sistólica.
- `diaBP`: Presión arterial diastólica.
- `BMI`: Índice de masa corporal.
- `heartRate`: Ritmo cardíaco.
- `glucose`: Nivel de glucosa.
- `TenYearCHD`: Indica si el paciente sufrió una enfermedad coronaria en los últimos 10 años (0: No, 1: Sí).

## Objetivos del Proyecto

1. **Carga y Exploración de Datos**: Cargar los datos y explorar las características de las variables, eliminando datos nulos o incorrectos.
2. **Análisis Descriptivo**: Escoger tres variables cuantitativas y realizar un análisis descriptivo, utilizando indicadores y gráficos para identificar cuál de ellas presenta mayor dispersión.
3. **Eliminación de Outliers**: Eliminar los datos atípicos para obtener un dataset "limpio" y realizar análisis posteriores sobre este conjunto.
4. **Análisis de Correlación**: Identificar qué variables cuantitativas presentan mayor correlación entre sí y analizar los resultados.
5. **Cálculo de Probabilidad Condicional**: Calcular la probabilidad de que un paciente sea hombre, dado que pertenece al mayor cuartil de la variable BMI.
6. **Prueba de Hipótesis sobre el Ritmo Cardíaco**: Evaluar si es razonable afirmar que el ritmo cardíaco promedio de una persona cualquiera es 75, explicando y justificando los resultados.
7. **Análisis del Consumo de Cigarrillos**: Investigar si ser hombre influye en el promedio de cigarrillos consumidos por día dentro del grupo de pacientes fumadores.
8. **Modelo de Regresión Lineal**: Construir un modelo de regresión lineal para relacionar el índice de masa corporal (BMI) con otras 6 variables del dataset (incluyendo al menos dos variables cualitativas). Evaluar y analizar el modelo.
9. **Modelo de Regresión Logística**: Construir un modelo de regresión logística para predecir el riesgo de sufrir una enfermedad coronaria en los próximos diez años. Evaluar el balanceo de los datos y la eficacia del modelo.
10. **Comparación de Modelos por Grupos**: Dividir los modelos de regresión anteriores en dos grupos, según una variable categórica, y comparar los resultados obtenidos.

## Herramientas y Bibliotecas Utilizadas

- **Python**: Lenguaje de programación utilizado para la manipulación de datos, análisis y construcción de modelos.
- **Pandas**: Para la manipulación y análisis de datos.
- **Matplotlib y Seaborn**: Para la visualización de datos.
- **Scikit-learn**: Para la construcción de modelos de regresión lineal y logística, y para métricas de evaluación de modelos.
- **Scipy**: Para la realización de pruebas estadísticas.

## Estructura del Proyecto

1. **Carga y Preprocesamiento de Datos**: Limpieza inicial de datos y eliminación de valores nulos e incorrectos.
2. **Análisis Exploratorio y Descriptivo**: Exploración de variables, generación de estadísticas descriptivas y visualización de la dispersión de datos.
3. **Análisis de Outliers y Correlaciones**: Identificación y eliminación de outliers y análisis de correlaciones entre variables cuantitativas.
4. **Pruebas de Hipótesis**: Realización de pruebas estadísticas para verificar hipótesis sobre el ritmo cardíaco y el consumo de cigarrillos.
5. **Modelado Predictivo**:
   - **Regresión Lineal**: Para predecir el índice de masa corporal basado en otras variables.
   - **Regresión Logística**: Para predecir el riesgo de enfermedad coronaria en un plazo de diez años.
6. **Comparación de Modelos**: Análisis de modelos segmentados por género y comparación de resultados.

## Resultados Esperados

- Identificación de factores de riesgo para enfermedades cardiovasculares.
- Modelos predictivos efectivos para estimar el índice de masa corporal y el riesgo de enfermedad coronaria.
- Conclusiones sobre cómo variables demográficas y clínicas afectan los riesgos cardiovasculares, con posibles recomendaciones para la prevención de enfermedades.

## Contribución

Este proyecto tiene el potencial de contribuir a estudios sobre prevención de enfermedades cardiovasculares mediante el análisis de factores de riesgo y la construcción de modelos predictivos. El pronóstico temprano puede mejorar las decisiones sobre estilos de vida y tratamientos, reduciendo así el impacto de las enfermedades cardiovasculares en la población.

---

**Nota**: Asegúrate de tener las bibliotecas necesarias instaladas antes de ejecutar el código.
