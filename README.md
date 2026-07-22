# AWS Academy TEC

Repositorio académico con materiales de apoyo desarrollados para los cursos de **AWS Academy impartidos en el Tecnológico de Costa Rica (TEC)**.

El repositorio reúne notebooks utilizadas en diferentes cursos y laboratorios relacionados con computación en la nube, aprendizaje automático, procesamiento de lenguaje natural e inteligencia artificial generativa. Cada notebook conserva la estructura y funcionalidad del laboratorio original, pero incorpora documentación adicional para facilitar su comprensión y seguimiento.

## Propósito del repositorio

El objetivo principal es proporcionar materiales que permitan comprender no solo cómo ejecutar cada laboratorio, sino también qué se está realizando en cada etapa, por qué se utilizan determinadas herramientas y cómo deben interpretarse los resultados obtenidos.

Las notebooks incluyen explicaciones en lenguaje claro, comentarios dentro del código, descripciones de las bibliotecas utilizadas y orientaciones para interpretar métricas, gráficas, predicciones y resultados intermedios.

Este material está dirigido tanto a estudiantes con experiencia previa en programación como a personas que están comenzando a trabajar con Python, aprendizaje automático y servicios de AWS.

## Contenido

El repositorio puede incluir materiales correspondientes a cursos como:

* AWS Academy Cloud Foundations
* AWS Academy Machine Learning Foundations
* AWS Academy Natural Language Processing Foundations
* AWS Academy Generative AI Foundations
* Laboratorios complementarios de análisis de datos e inteligencia artificial

Dependiendo del curso, las notebooks pueden abordar temas como:

* Preparación y exploración de datos
* Limpieza y transformación de información
* Entrenamiento de modelos de aprendizaje automático
* Evaluación mediante métricas y matrices de confusión
* Clasificación de texto
* Análisis de sentimiento
* Vectorización y representación numérica de texto
* Ajuste de hiperparámetros
* Uso de algoritmos como XGBoost
* Uso de servicios administrados de AWS
* Ejecución de experimentos en Amazon SageMaker
* Procesamiento de lenguaje natural con Amazon Comprehend
* Entrenamiento de modelos con Amazon BlazingText
* Aplicaciones introductorias de inteligencia artificial generativa

## Organización de las notebooks

Las notebooks están organizadas en secciones que siguen el flujo natural de cada laboratorio:

1. Presentación del objetivo del ejercicio.
2. Importación de bibliotecas y herramientas.
3. Carga de los datos.
4. Exploración inicial de la información.
5. Preparación y transformación de los datos.
6. Entrenamiento de los modelos.
7. Generación de predicciones.
8. Evaluación de resultados.
9. Comparación entre métodos o configuraciones.
10. Interpretación de los resultados obtenidos.

Cada sección incluye una breve introducción que explica qué se realizará, por qué esa etapa es necesaria y qué resultado se espera obtener.

## Documentación incorporada

Para facilitar la lectura de las notebooks, se agregaron:

* Comentarios breves dentro de los bloques de código.
* Explicaciones sobre el propósito de cada instrucción.
* Descripciones sencillas de las bibliotecas utilizadas.
* Títulos y subtítulos que identifican claramente cada etapa.
* Orientaciones para interpretar métricas, tablas y gráficas.
* Explicaciones sobre los resultados más relevantes.
* Contexto adicional para comprender el flujo completo del laboratorio.

La documentación está diseñada para acompañar el código sin alterar su funcionamiento original.

## Conservación del código original

Las notebooks documentadas mantienen:

* Las instrucciones originales.
* Los nombres de las variables y funciones.
* El orden de ejecución.
* Las bibliotecas utilizadas.
* Los algoritmos implementados.
* Las gráficas generadas.
* Los cálculos y operaciones.
* La funcionalidad definida en cada laboratorio.

No se busca sustituir, optimizar o rediseñar los laboratorios originales. El propósito es mejorar su presentación y hacer que el contenido técnico sea más accesible.

## Requisitos generales

Los requisitos pueden variar según la notebook. En términos generales, se recomienda contar con:

* Una cuenta con acceso a AWS Academy.
* Acceso a Amazon SageMaker cuando el laboratorio lo requiera.
* Python 3.
* Jupyter Notebook o JupyterLab.
* Las bibliotecas indicadas en cada notebook.
* Los permisos y recursos de AWS definidos para cada laboratorio.

Algunos ejercicios deben ejecutarse dentro del entorno proporcionado por AWS Academy, ya que pueden depender de roles, permisos, conjuntos de datos, buckets de Amazon S3 o servicios configurados específicamente para el curso.

## Uso del repositorio

1. Seleccione la carpeta correspondiente al curso o laboratorio.
2. Abra la notebook que desea utilizar.
3. Lea la introducción y los objetivos de cada sección.
4. Ejecute las celdas siguiendo el orden establecido.
5. Revise los comentarios incorporados en el código.
6. Analice las métricas, gráficas y resultados generados.
7. Consulte las indicaciones particulares incluidas en cada notebook.

Para abrir una notebook localmente puede utilizar:

```bash
jupyter notebook
```

También puede trabajar con JupyterLab:

```bash
jupyter lab
```

Cuando el laboratorio dependa de servicios de AWS, se recomienda utilizar directamente el entorno de Amazon SageMaker proporcionado por AWS Academy.

## Consideraciones importantes

Los materiales de este repositorio tienen fines educativos y de apoyo docente.

La disponibilidad de servicios, interfaces, versiones de bibliotecas y recursos de AWS puede cambiar con el tiempo. Por esta razón, algunos laboratorios podrían requerir el entorno específico definido por AWS Academy para funcionar correctamente.

Las credenciales, claves de acceso, nombres de usuario, tokens y demás información sensible no deben almacenarse en las notebooks ni publicarse en el repositorio.

## Buenas prácticas

Antes de ejecutar una notebook:

* Verifique que está utilizando el entorno correcto.
* Confirme que las bibliotecas requeridas están instaladas.
* Revise que los servicios de AWS necesarios estén disponibles.
* Ejecute las celdas en el orden establecido.
* Reinicie el kernel cuando se modifiquen dependencias.
* No publique información confidencial o credenciales.
* Revise los costos asociados con los recursos utilizados fuera del entorno controlado de AWS Academy.

## Audiencia

Este repositorio está dirigido principalmente a:

* Estudiantes de los cursos de AWS Academy.
* Docentes que utilizan notebooks como material de apoyo.
* Profesionales que desean introducirse en servicios de inteligencia artificial en AWS.
* Personas interesadas en comprender laboratorios de aprendizaje automático y procesamiento de lenguaje natural.
* Usuarios que requieren explicaciones adicionales para seguir el código paso a paso.

## Alcance

El contenido complementa las guías oficiales y los materiales proporcionados por AWS Academy. No sustituye la documentación oficial de AWS, las instrucciones de los laboratorios ni las indicaciones específicas del instructor.

Las explicaciones incorporadas buscan facilitar el aprendizaje, relacionar las instrucciones con los objetivos del laboratorio y permitir una interpretación más clara de los resultados.

## Institución

**AWS Academy TEC**
Tecnológico de Costa Rica
Costa Rica

## Licencia y uso académico

El uso de estos materiales debe respetar las condiciones establecidas por AWS Academy, Amazon Web Services, el Tecnológico de Costa Rica y las licencias correspondientes a las bibliotecas, datos y recursos incluidos en cada laboratorio.

Los contenidos adicionales de documentación y explicación se proporcionan con fines académicos y educativos.
