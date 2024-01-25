# Map_and_Data
Contiene los código en python para la construcción de mapas dinámicos para representar sobre ellos los datos que se desee

Visualización Interactiva de Datos Socioeconómicos y de Desempleo en Mapa
Descripción
Este proyecto proporciona una herramienta de visualización interactiva que integra datos socioeconómicos y de desempleo con datos geoespaciales para representarlos en un mapa interactivo. Utilizando Python junto con las bibliotecas Folium, Pandas y GeoPandas, este código permite fusionar datos de archivos Excel con información geográfica de comarcas, presentando una representación visual intuitiva y detallada de diversos indicadores económicos por comarca.

Objetivo
El objetivo principal de este proyecto es facilitar la comprensión de los datos socioeconómicos y de desempleo a nivel regional, ofreciendo una herramienta que permite visualizar estos datos de manera geográfica. Esto es especialmente útil para análisis socioeconómicos, estudios demográficos y planificación regional, proporcionando una manera interactiva y visual de explorar los datos.

Características
Integración de Datos: Combina datos de múltiples fuentes en un único mapa interactivo.
Visualización Geoespacial: Representa datos por comarca en un mapa, usando GeoJSON para la geolocalización.
Interactividad: Permite a los usuarios explorar datos específicos por comarca a través de tooltips interactivos.
Flexibilidad: Código adaptable para incorporar distintos conjuntos de datos socioeconómicos.
Uso
Para utilizar este código, necesitarás tener instaladas las bibliotecas de Python: Folium, Pandas, y GeoPandas. El código carga datos de archivos Excel y los combina con un archivo GeoJSON que contiene la información geográfica de las comarcas. Los resultados se visualizan en un mapa interactivo generado con Folium, donde cada comarca puede ser explorada para mostrar datos específicos.

Preparación de Datos
t8598com.xlsx: Contiene datos socioeconómicos como Agricultura, Industria, Construcción, Servicios y Total.(Datos de Afiliación a la Seguidad Social por serctores)
t4299com.xlsx: Incluye datos de desempleo, diferenciados por género y total.
divisions-administratives-v2r1-comarques-500000-20230928.json: Archivo GeoJSON con la información geográfica de las comarcas.
Ejecución del Código
Instalar las dependencias requeridas: pandas, folium, geopandas.
Asegúrate de que los archivos Excel y el archivo GeoJSON estén correctamente ubicados y sus rutas actualizadas en el código.
Ejecutar el script para visualizar el mapa.
Contribuciones
Las contribuciones a este proyecto son bienvenidas. Si tienes sugerencias para mejorar la herramienta o deseas añadir nuevas funcionalidades, no dudes en crear un pull request o abrir un issue.
