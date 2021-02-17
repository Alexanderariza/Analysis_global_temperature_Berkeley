# Análisi de la temperatura global (Base de datos de Berkley)
<p><center> <img src="https://github.com/Alexanderariza/Analysis_nivel_CO2_Atm/blob/main/Img/logo_heat.png" width="1000"/> </p></center>
# Técnicas y Aplicaciones de Teledetección: Cambio Climático-Riesgos y Desastres
***
## Cambio climático: Análisis de niveles de CO2 en la atmósfera
En este cuaderno vamos a explorar parte del contenido de la unidad:<br>
<ul>
<il> II. Integración de información para explicar relaciones causa y efecto.</li><br>
<il> III. Procesamiento de datos en la nube para el análisis de desastres.</li><br>
<il> VI. Análisis de Series Temporales de Datos en procesos relacionados con la biosfera.</li><br></ul>
Mediante el análisis de los cambios en las temperaturas medias globales, así como el aumento de las concentraciones de CO2 en la atmósfera.
## ¿Como funciona?
1. Puede [descargar](Analysis_of_CO2_levels_in_the_atmosphere.ipynb) el cuaderno de Jupyter Notebook y utilizar los recursos de computación de su PC. 
2. Otra opción alternativa, es el de [**Google Colab**]( https://colab.research.google.com). Como entorno de computación en la nube para cuadernos de Jupyter, la cual aprovecha los recursos técnicos externos, permitiendo que esta herramienta se pueda aplicar en dispositivos con una potencia de computo más limitada, incluidos dispositivos móviles como teléfonos y tabletas, en áreas con escaso ancho de banda. Para ello puede acceder a esta versión directamente haciendo clic en el icono de abajo.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alexanderariza/Analisis_nivel_CO2_-atm-sfera/blob/main/Colab/An%C3%A1lisis_nivel_CO2_en_la_atmosfera.ipynb)

## Acerca de este conjunto de datos:
Par esta práctica, trabajaremos con una compilación más reciente elaborada por **Berkeley Earth** , afiliado al Laboratorio Nacional Lawrence Berkeley. El estudio de temperatura de la superficie terrestre de Berkeley combina 1.600 millones de informes de temperatura de 16 archivos preexistentes. Está muy bien empaquetado y permite dividirlo en subconjuntos interesantes (por ejemplo, por país). Publican los datos de origen y el código de las transformaciones que aplicaron. También utilizan métodos que permiten incluir observaciones meteorológicas de series de tiempo más cortas, lo que significa que se deben desechar menos observaciones.

## Datos de temperatura de la superficie terrestre
### Explorando las temperaturas globales desde 1750:
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
<i>¿Cómo han cambiado los niveles de dióxido de carbono atmosférico en los últimos sesenta años?<br> 
¿Cómo cambian las concentraciones de dióxido de carbono estacionalmente?<br> 
¿Qué crees que causa este ciclo estacional?<br> 
¿Cuándo superarán los niveles de dióxido de carbono las 450 ppm partes por millón?<br></i>
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
