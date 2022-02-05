# Análisis de la temperatura global 
<p><center> <img src="https://github.com/Alexanderariza/Analysis_nivel_CO2_Atm/blob/main/Img/logo_heat.png" width="1000"/> </p></center>

# Técnicas y Aplicaciones de Teledetección: Cambio Climático-Riesgos y Desastres<br>
***
## Cambio climático: Análisis de la temperatura global (Base de datos de Berkley)

<p>Este material se basa en el trabajo apoyado por el Centro Nacional de Investigación Atmosférica, una importante instalación patrocinada por la National Science Foundation y gestionada por la University Corporation for Atmospheric Research. Las opiniones, resultados y conclusiones o recomendaciones expresadas en este material no reflejan necesariamente la opinión de la National Science Foundation ni de la UCM.</p>
<p><center> <img src="http://berkeleyearth.org/wp-content/uploads/2021/01/2020_Global_Map-1024x571.png" width="600"/> </p></center>
En este cuaderno vamos a explorar parte del contenido de la unidad:<br>
<ul>
<il> II. Integración de información para explicar relaciones causa y efecto.</li><br>
<il> III. Procesamiento de datos en la nube para el análisis de desastres.</li><br>
<il> VI. Análisis de Series Temporales de Datos en procesos relacionados con la biosfera.</li><br></ul>
Mediante el análisis de los cambios en las temperaturas medias globales, así como el aumento de las concentraciones de CO2 en la atmósfera.<br>

## ¿Como funciona?
1. Puede [descargar](https://github.com/Alexanderariza/Analysis_global_temperature_Berkeley/tree/main/colab) el cuaderno de Jupyter Notebook y utilizar los recursos de computación de su PC. 
2. Otra opción alternativa, es el de [**Google Colab**]( https://colab.research.google.com). Como entorno de computación en la nube para cuadernos de Jupyter, la cual aprovecha los recursos técnicos externos, permitiendo que esta herramienta se pueda aplicar en dispositivos con una potencia de computo más limitada, incluidos dispositivos móviles como teléfonos y tabletas, en áreas con escaso ancho de banda. Para ello puede acceder a esta versión directamente haciendo clic en el icono de abajo.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-fzBk_CS0lWSKjbK3qx2cC7aDegq_fGw#scrollTo=SXzc_43uZjAl)<br>

## Acerca de este conjunto de datos:
Par esta práctica, trabajaremos con una compilación más reciente elaborada por **Berkeley Earth** , afiliado al Laboratorio Nacional Lawrence Berkeley. El estudio de temperatura de la superficie terrestre de Berkeley combina 1.600 millones de informes de temperatura de 16 archivos preexistentes. Está muy bien empaquetado y permite dividirlo en subconjuntos interesantes (por ejemplo, por país). Publican los datos de origen y el código de las transformaciones que aplicaron. También utilizan métodos que permiten incluir observaciones meteorológicas de series de tiempo más cortas, lo que significa que se deben desechar menos observaciones.

## Datos de temperatura de la superficie terrestre
### Explorando las temperaturas globales desde 1750:
<p><center> <img src="http://berkeleyearth.org/wp-content/uploads/2021/01/2020_Land_and_Ocean-1024x577.png" width="600"/> </p></center>
Existe una variedad de organizaciones que recopilan datos de tendencias climáticas. Los tres conjuntos de datos de temperatura terrestre y oceánica más citados son MLOST de NOAA, GISTEMP de NASA y HadCrut del Reino Unido.
## Contenido
Dentro del conjunto de datos que veremos están:
Temperaturas globales terrestres y oceánicas y terrestres ( GlobalTemperatures.csv ):
•	Fecha: comienza en 1750 para la temperatura promedio de la tierra y 1850 para las temperaturas máxima y mínima de la tierra y las temperaturas globales del océano y la tierra<br>
•	LandAverageTemperature: temperatura media global de la tierra en grados Celsius<br>
•	LandAverageTemperatureUncertainty: el intervalo de confianza del 95% alrededor del promedio<br>
•	LandMaxTemperature: temperatura máxima promedio global de la tierra en grados Celsius<br>
•	LandMaxTemperatureUncertainty: el intervalo de confianza del 95% alrededor de la temperatura máxima de la tierra<br>
•	LandMinTemperature: temperatura mínima promedio global de la tierra en grados Celsius<br>
•	LandMinTemperatureUncertainty: el intervalo de confianza del 95% alrededor de la temperatura mínima de la tierra.<br>
•	LandAndOceanAverageTemperature: temperatura media global de la tierra y el océano en grados Celsius<br>
•	LandAndOceanAverageTemperatureUncertainty: el intervalo de confianza del 95% alrededor de la temperatura media mundial de la tierra y el océano.<br>
Otros archivos incluyen:
•	Temperatura media global de la tierra por país ( GlobalLandTemperaturesByCountry.csv )<br>
•	Temperatura promedio global de la tierra por estado ( GlobalLandTemperaturesByState.csv )<br>
•	Temperaturas globales de la tierra por ciudad principal ( GlobalLandTemperaturesByMajorCity.csv )<br>
•	Temperaturas globales de la tierra por ciudad ( GlobalLandTemperaturesByCity.csv )<br>
## Referencia
Los datos brutos provienen de la página de datos de [Berkeley Earth](http://berkeleyearth.org/data/)
## Preguntas a resolver:
<i>¿Cómo han cambiado los niveles de Temperatura en los últimos 100 años?<br> 
¿Cómo cambian las distribuciones medias de Temperatura?<br> 
¿Qué crees que causa este incremento progresivo?<br> 
¿Que paises superarán los valores medios de incremento de temperatura en ºC?<br></i>
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
