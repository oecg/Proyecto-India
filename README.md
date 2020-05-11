# Proyecto India

# <center> Clasificación de Péptidos Antimicrobianos
**Universidad Nacional de Colombia**
  
En las últimas décadas, la resistencia bacteriana se ha convertido en una de las problemáticas más graves a nivel mundial. Un agravante de esta problemática es que existe un declive en la búsqueda y desarrollo de nuevas moléculas antimicrobianas que puedan ser usadas contra bacterias resistentes a los antibióticos actuales. En parte, la disminución del interés en la investigación y desarrollo de nuevos antibióticos se debe tanto al costo y el tiempo que requieren las pruebas en laboratorio necesarias en la generación de nuevas moléculas antimicrobianas, como al escaso retorno de la inversión que esta representa para las empresas farmacéuticas.

Como parte de solución a la problemática, los péptidos antimicrobianos (o AMPs, de su sigla en inglés Antimicrobial Peptides) han tomado importancia en el desarrollo de nuevos antibióticos por su rol como agente inhibidor, no solo de bacterias sino también de virus, hongos y parásitos, entre otros (Porto et al., 2017; Yoshida et al., 2018). Los AMPs son parte esencial de todos los organismos vivos y configuran la primera línea de defensa contra bacterias, microbios y parásitos. Este tipo de péptidos causan la muerte de las bacterias y los microbios, bien sea interfiriendo las funcionalidades de la membrana celular o interrumpiendo sus funciones intracelulares (Brogden, 2005; Yeaman & Yount, 2003). De ahí la importancia que tienen el determinar la capacidad antimicrobiana de un péptido.

Si bien la identificación de péptidos antimicrobianos se ha desarrollado de manera manual, en los últimos años se ha venido realizando importantes avances en lo que respecta al uso de los algoritmos de inteligencia artificial. Esto puede tener un impacto positivo en el contexto farmacéutico dado que el uso de algoritmos de aprendizaje automático puede reducir los costos y el tiempo empleados en el proceso de búsqueda y diseño de nuevas biomoléculas sintéticas para la producción de antibióticos.

Lo anterior, ha motivado a que los grupos de investigación en Biología Funcional e Investigación y Desarrollo en Inteligencia Artificial (GIDIA), ambos de Universidad Nacional, sede Medellín, y el grupo de investigación en Automática Electrónica y Ciencias Computacionales (AEyCC) del ITM, unan sus esfuerzos en la búsqueda y construcción de soluciones computacionales que apoyen la investigación y desarrollo de nuevas moléculas antimicrobianas.

Como resultado parcial se ha recopilado, de las diferentes bases de datos de péptidos disponibles, péptidos que se han identificado que pertenecen a una de dos clases: antimicrobianos y NO-antimicrobianos. Para dicho conjunto de péptidos se ha calculado aproximadamente 1700 descriptores a partir de propiedades como la carga eléctrica, la hidrofobicidad, el momento hidrofóbico, el punto isoeléctrico, la estructura primaria y otras características fisicoquímicas de los péptidos.

# Resultados y conclusiones

Figura 1: Grafico de Barras no antimicrobianos (0) y antimicrobianos (1)

![alt text](https://github.com/oecorrechag/Proyecto-India/blob/master/plot.png)

Se Ajustaron 3 modelos, un Bosque Aleatorio, una Red Neuronal y una Regresión Logística. Se calificaron con las métricas de f1_score, accuracy, precision_score, recall_score y matriz de confusión, dándole más relevancia a esta última.

Figura 2: Matriz de Confusión del ajuste de la red neuronal.

![alt text](https://github.com/oecorrechag/Proyecto-India/blob/master/matriz.png)

Al ajustar los modelos se obtuvieron resultados similares, con pocas diferencias, sin embargo, la diferencia notoria es el tiempo de ejecución, ya que mientras los tiempos de ejecución del Bosque Aleatorio y la Regresión Logística son mucho menores que los de la Red Neuronal. Se recomendaría un modelo más simple como la Regresión Logística por su consistencia en las métricas numéricas y podria mejorarse con un experto en el tema, sin embargo, si se cuenta con más recursos computacionales y más observaciones se podría usar la Red Neuronal.

### Bibliografia
• Cournapeau, D., (2007), scikit-learn. Recuperado de: https://scikit-learn.org
