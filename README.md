## **_PROYECTO INDIVIDUAL 2 - DATA ANALYST_**

---

## **INTRODUCCIÓN**

El siguiente proyecto consta de la realización de un análisis de datos correspondiente al sector de telecomunicaciones en Argentina, con datos provenientes de ENACOM (Ente Nacional de Comunicaciones). Contando con un EDA trabajado en Python y visualizaciones mediante dashboards en PowerBI.

## **Objetivo**

Obtener información valiosa a partir de datos históricos del sector de telecomunicaciones, con el fin de profundizar en la rama de internet visualizando los distintos tipos de datos trabajados, logrando identificar distintas oportunidades de inversión y mejoras.

## **Directorios y archivos del repositorio**

- [**Datos Originales**:](Datos) Directorio donde se disponibilizan las fuentes de datos sin procesar. Son todos archivos excel.
- [**Datos Procesados Para PowerBI**:](Datos%20Procesados%20Para%20PowerBI) Directorio donde se disponibilizan las fuentes de datos procesadas, listas para trabajarse en 
  PowerBI.
- [**EDA**:](EDA.ipynb) Archivo .ipynb donde se realizó el correspondiente EDA (Anális Exploratorio de Datos).
- [**Dashboard**:](PowerBI_ProyectoIndividual2.pbix) Reporte realizado en PowerBI.

## **ETAPAS DEL PROYECTO**

---

### **1) Estudio de la fuente de datos y EDA (Exploratory Data Analysis)**

En primer lugar se realiza un estudio de las fuentes de datos disponibilizadas en archivos `.xlsx` en la página web de ENACOM (_Ente Nacional de Comunicaciones_) https://datosabiertos.enacom.gob.ar/
Se investigan otras fuentes de datos para agregar mas información y valor al análisis, entre ellas, datos del Banco mundial desde su pagina web.
Se hace una exploración de datos con mediante Python con la ayuda de bibliotecas como Pandas y Numpy (revisión de duplicados, tipos de datos, valores faltantes y errores en los datos tomando las acciones necesarias.)

### **2) ETL (Extract, Transform and Load)**

En el archivo de -[**EDA**:](EDA.ipynb) se mencionan los pasos realizados para transformar y limpiar los datos. También se cuenta con la ayuda de gráficas, para mejor visualización, mediante las herramientas de Matplotlib y Seaborn.

### **3) Construcción del Dashboard**

La postura que se tomó para llevar a cabo la construcción del dashboard se basó en reconocer los distintos tipos de tecnologías, velocidades y el acceso a estas por cada provincia perteneciente a Argentina.

- 1) Muestra de los datos mas oportunos como totales de ingresos y tecnologías y accesos a los diferentes tipos de tecnologías.
- 2) Visualización de las velocidades con mayor consumo así como el crecimiento a lo largo del rango temporal 2014-2024 de tecnologías
- 3) Observación de los accesos, tanto en hogares como poblacionalmente hablando, de distintas categorías de BAF.

## **CONCLUSIONES DE LOS DATOS TRABAJADOS**

Luego de un amplio EDA, ETL y construcciones en de gráficas en PowerBI, se puede llegar a la conclusión de que Argentina generó, en el último año (2023) unos ingresos totales de $520 millones. Siendo Buenos Aires, Capital Federal, Santa Fé y Córdoba las provincias con mayor presencia de tecnologías BAF y mayor consumo en MBPS (50, 6, 100, 10, 300). 
Dentro de estas tecnologías, las que van en crecimiento por amplia diferencia, son Cable Módem y Fibra Óptica, mientras que ADSL viene en disminución. Por lo que sería una buena oportunidad de invertir en estas mismas en las provincias antes menciondas.
Respecto a los accesos en hogares y la población, como es esperable ambos vienen en subida, pero se logra observar que hay mayores alcances en hogares por lo que no se debería pasar por alto. 
Respecto al resto de provincias, se encuentran bastante atrasadas ya sea en tecnologías o velocidad, por lo que se podría tratar de no centralizar tanto y ser distribuido de una manera mas equitativa llegando a distintos puntos del país para mejor comodidad de los habitantes.
