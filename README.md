# Proyecto 3 
# Visualización de información

_Integrantes:_
- David Blanco: 2020053806
- 

El objetivo de este proyecto es crear tres diferentes visualizaciones de redes utilizando un modelo cliente-servidor, en donde el servidor generará el modelo geométrico de la red y el cliente permitirá visualizar e interactuar con dicho modelo.

## Introduccion

El Proyecto tiene como objetivo crear tres visualizaciones diferentes de (forced direct graph) utilizando un modelo cliente-servidor. En este modelo, el servidor generará el modelo geométrico de la red, mientras que el cliente permitirá visualizar e interactuar con dicho modelo. Para lograr esto, se trabajará con tres conjuntos de datos específicos: la red de trastornos y genes patológicos (Diseases), el estudio topológico de la web EuroSiS (Eurosis), y las redes de contacto en un centro de enseñanza primaria (School). Cada uno de estos conjuntos de datos se procesará para generar visualizaciones dinámicas mediante D3.js, utilizando la técnica de grafo de fuerzas. Estas visualizaciones permitirán a los usuarios explorar y analizar las redes de manera interactiva, ofreciendo funcionalidades como la consulta de etiquetas de nodos, zoom y pan.

## Descripción del problema

Se deberá generar visualizaciones para cada uno de los conjuntos de datos que se detallan a continuación:

1. diseases: consiste de la red de trastornos y genes patológicos vinculados por asociaciones conocidas entre genes y trastornos, lo que indica el origen genético común de muchas enfermedades. El conjunto de datos original puede consultarse como: The Human Disease Network, Goh K-I, Cusick ME, Valle D, Childs B, Vidal M, Barabási A-L (2007), Proc Natl Acad Sci USA 104:8685-8690.

2. eurosis: Estudio topológico de la web EuroSiS: Mapeo de las interacciones entre los actores de Science in Society en la Web de 12 países europeos.

3. school: Este conjunto de datos forma parte de án estudio de las redes de contacto en un centro de enseñanza primaria, del que se informa en el artículo High-Resolution Measurements of Face-to-Face Contact Patterns in a Primary School.

**Generación del modelo geométrico**

Se deben crear tres funciones en Netlify que lean los anteriores archivos de datos y generen los respectivos modelos geométricos, utilizando D3.js, mediante la técnica de grafo de fuerzas (force-directed layout). Note que no se debe generar el SVG directamente en el servidor sino que eso será realizado por el cliente.

**Visualización en el cliente (browser)**

Se debe crear una página web, utilizando D3.js,, que permita visualizar cada uno de los archivos del modelo geométrico generados en Netlify. Esta visualización debe permitir consultar la etiqueta de cada nodo seleccionado, así como realizar acercamientos (zoom), alejamientos (unzoom), y corrimientos (pan).

## Fuentes de datos

Las fuentes de datos son orígenes desde los cuales se pueden obtener datos. Estos pueden ser de diversos tipos y pueden provenir de diferentes lugares y formatos. Las fuentes de datos son esenciales en el campo de la informática, la investigación y la toma de decisiones empresariales, ya que proporcionan la información necesaria para análisis, informes y desarrollo de estrategias. A continuación, se presentan algunas definiciones y ejemplos de diferentes tipos de fuentes de datos:

#### Fuentes de datos primarios

Estos se pueden definir como: “se obtienen originalmente y se documentan por primera vez”(Stewart, 2024). El proceso para recopilar datos primarios utiliza estrategias que facilitan la obtención de los mismos. Para ellos se utilizan métodos como los siguientes:

- Encuestas y cuestionarios
- Entrevistas
- Grupos de discusión
- Observaciones
- Experimentos

#### Fuentes de datos secundarios

Según Lauren Steward, se pueden definir como datos que se basan en fuentes ya existentes.

## Descripción detallada y explicación de las secciones principales del documento.

## Conclusiones


## Bibliografia:

Stewart, L. (2024, March 13). Datos primarios frente a datos secundarios: Distinciones clave y usos. ATLAS.ti. https://atlasti.com/es/research-hub/datos-primarios-secundarios
