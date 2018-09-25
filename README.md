# Comportamiento de los suicidios en Colombia - 2015

En Colombia, al igual que en la mayoría de los países del mundo, el volumen de hombres que se quitan la vida es abrumadoramente superior al de las mujeres. En esta visualización se muestra la tendencia de suicidio de los géneros en rangos de edades durante el 2015.

# Objetivo del proyecto  
Identificar el rango de edad donde los sexos tienden al suicidio  

# Tecnologías usadas
  - <a href="https://d3js.org/"> D3js V5 </a>
  - <a href="https://www.sublimetext.com/"> Sublime text 3 </a>

# Cómo se corre 
  - git clone https://github.com/armandorp10/suicidas_en_colombia.git
  - Luego, abrir el index.html con firefox web browser 
  - Alternativa, instalar un servidor web(apache, IIS, etc) y montar el proyecto en este servidor para poder visualizarlo

# link a la página del proyecto
  https://armandorp10.github.io/suicidas_en_colombia/
  
# Screenshot 
<img src="https://raw.githubusercontent.com/armandorp10/suicidas_en_colombia/master/images/Screenshot.png" alt="Screenshot.png">

# What
Dataset Type: Table <br>
Attributes: <br>
  grupo_de_edad: Categorical <br>
  hombre_1: Ordered - quantitative <br> 
  hombre_2: Ordered - quantitative <br>
  mujer_1: Ordered - quantitative <br>
  mujer_2: Ordered - quantitative <br>
  tasa_hombre: Ordered - quantitative <br>
  tasa_mujer: Ordered - quantitative <br>
  total_1: Ordered - quantitative <br>
  total_2: Ordered - quantitative <br>
Dataset Availability: static 

# Why 
- Identificar el rango de edad donde los sexos tienden al suicidio. (Tamara, Identify - trend )
- Sumarizar la distribución de los suicidios de los sexos con respecto a rangos de edades. (Tamara, summarize - distribution) 
- Localizar las edades donde hay mayor y menor probabilidad de suicido de los sexos (Tamara, locate - extremes) 
- Comparar la similaridad de las curvas al suicidio de ambos sexos en los rangos de edades (Tamara, Compare - Similarity) 

# How
Marks  
líneas y puntos
Channels  
Position-> Vertical  (Atributo ordenado porcentaje hombre y/o mujeres)
Position-> Horizontal (Atributo categórico rango de edades)
Color -> hue (Atributo categórico género masculino y femenino)

Encode Arrange -> Express (porcentaje de hombres y/o mujeres. Position-> Vertical )
Encode Arrange -> Express (rango de edades. Position-> Horizontal )
Map -> Color -> Hue (género )

# Insights
- Un gran porcentaje de las mujeres tienden a suicidarse en su juventud
- El hombre tiende a tener una mayor tasa de suicidio al entrar a una edad madura


Made by <a href="https://github.com/armandorp10">Diego Prens Ramos</a>, licensed under MIT
