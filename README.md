# Ecommerce de productos electrónicos
Este proyecto tiene como objetivo explorar y analizar datos de un negocio ecommerce de productos electrónicos utilizando técnicas de análisis de datos, modelado y visualización. Para esto utilizamos un dataset público alojado en Kaggle.com [( link del dataset)](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-electronics-store), estas son las características más resaltantes del conjunto de datos: 
- El archivo contiene datos de comportamiento durante 5 meses (octubre de 2019 – febrero de 2020) de una tienda de electrónica en línea. 
- Cada fila del archivo representa un evento. Todos los eventos están relacionados con productos y usuarios. recopilados por el proyecto Open CDP. 
- Para más detalles respecto a la estructura de los campos (columnas) [click aquí.](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-electronics-store)

## Las 4 preguntas que buscamos responder :

- _**Ventas Mensuales**:_
  Queremos determinar cuánto se vendió en cada mes durante un período específico, desde septiembre de 2020 hasta febrero de 2021. Esto nos permitirá identificar patrones estacionales en las ventas.

- _**Horario de Mayor Ventas**:_
  Buscamos conocer a qué hora del día se producen más ventas durante el mismo período. Esto puede ser esencial para la planificación de recursos.

- _**Porcentaje de interacciones de Visitadores Web respecto al total de interacciones**:_
  Queremos calcular el porcentaje de visitantes web que interactúan de diferentes maneras, como visitas simples, interacciones con el carrito de compras, eliminación de productos del carrito y compras reales. Esto nos ayudará a entender mejor el comportamiento en línea de los visitantes.

- _**Categorías Más Vendidas**:_
Finalmente, identificaremos las cinco categorías de productos que generaron las mayores ventas durante los dos últimos meses, es decir, en enero y febrero de 2021. Esto puede proporcionar información valiosa sobre qué productos son más populares en ese período.
  
## Etapas clave del proceso de análisis de datos de este proyecto:
### Obtención de Datos desde Kaggle: 
Comenzamos por obtener un conjunto de datos público desde Kaggle. Esta información actúa como punto de partida para nuestro análisis y contiene datos relevantes para el negocio.

### Almacenamiento en AWS S3: 
Como parte de nuestra iniciativa para conocer los servicios de AWS, creamos un bucket en Amazon S3 para alojar este conjunto de datos. Esto nos permite aprovechar el poder y la escalabilidad de la nube de AWS y nos brinda la oportunidad de explorar sus servicios en el futuro.

### [Análisis Exploratorio en Python:](Analisis_exploratorio.ipynb)
Utilizamos Python para llevar a cabo un análisis exploratorio de los datos. Esta fase nos permite descubrir patrones, tendencias y relaciones en la información, lo que nos ayudará a entender mejor el funcionamiento del negocio.

### Modelado y Transformación de Datos en MySQL Server: 
Los datos se someten a un proceso de modelado y transformación en MySQL Server. Aquí, aplicamos diversas técnicas para limpiar y preparar los datos para su posterior análisis. Este paso es fundamental para garantizar la calidad de los datos.

### Análisis de Datos en MySQL Server: 
Luego de garantizar la calidad de los datos, analizaremos estos datos para responder las 4 preguntas clave detalladas anteriormente interactuando con el lenguaje MySQL. Este análisis proporciona información esencial para tomar decisiones informadas y estratégicas, permitiendo comprender mejor el rendimiento y el compromiso de los clientes en línea del ecommerce de productos electrónicos.

### Visualización de Datos en Power BI: 
Para comunicar los resultados de manera efectiva, utilizamos Power BI para crear visualizaciones interactivas. Estas visualizaciones proporcionarán una representación clara y concisa de los datos, lo que facilitará la comprensión de los hallazgos.


En síntesis, este proyecto tiene como objetivo explorar, transformar y visualizar datos para obtener información valiosa que respalde la toma de decisiones en el negocio del sector ecommerce de productos. Además, nuestra interacción con AWS S3 sienta las bases para futuras exploraciones en el ecosistema de AWS.

