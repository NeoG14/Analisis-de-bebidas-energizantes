# [Análisis  de datos aplicado a una nueva bebida energizante](Energizantes.ipynb)
## Planteamiento del Problema
MegaBoost es una marca de bebidas energizantes de Inglaterra y desea ingresar al mercado italiano. Hace algunos meses lanzaron su bebida en 10 ciudades de Italia.

El equipo de marketing está a cargo de incrementar el posicionamiento de la marca y la participación en el mercado, además de apoyar el desarrollo del producto. Para esto aplicaron una encuesta a 10.000 personas en esas 10 ciudades.

## Set de datos
- [Formato de encuesta realizada a 10.000 personas](metadata/encuesta_bebida_energizante.pdf)
- [Dataset principal (.csv) con 10.000 respuestas de la encuesta](data/dataset_bebida_energizante.csv)
- [Metadatos con la descripción de la información contenida en el set de datos](metadata/metadatos_dataset_bebida_energizante.txt)

## Metodología
- Tratamiento de datos: Limpieza de nulos, eliminación de duplicados y formateo de tipos de datos con `NumPy` y `Pandas` 
- Análisis exploratorio (EDA): Identificación de patrones de consumo por ciudad y grupo demográfico.
- Visualización: Generación de gráficos analíticos utilizando `Matplotlib`

## Tareas a realizar
Su labor es extraer los siguientes *insights* a partir de los datos:

- **Demográficos:**
    - ¿Quiénes prefieren esta bebida energética?
    - ¿Qué rangos de edad tienden a preferir la bebida?
 
- **Análisis de la competencia:**
    - ¿Quiénes son los actuales líderes del mercado?

- **Canales de mercadeo y conocimiento de la marca:**
    - ¿Cuál es el canal de mercadeo más efectivo?
    
- **Penetración de la marca:**
    - ¿Qué piensa la gente de nuestra marca?
    - ¿En qué ciudades debemos reforzar este posicionamiento?
    - ¿Por qué los consumidores prefieren otras marcas y no las nuestras?

- **Preferencias del consumidor:**
    - ¿Cuáles son los ingredientes preferidos?
    - ¿Qué tipo de paquetes son los preferidos?

- **Comportamientos de compra:**
    - ¿Dónde prefieren las personas comprar bebidas energizantes?
    - ¿Cuáles son las situaciones típicas de consumo de bebibas energéticas?
    - ¿Qué factores influyen más en las decisiones de compra de las personas?

- **Desarrollo de producto:**
    - ¿Qué área deberíamos priorizar para el desarrollo y mejora del producto?
