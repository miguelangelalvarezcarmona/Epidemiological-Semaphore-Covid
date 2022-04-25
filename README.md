#IMPORTANT#

Right now, the data from this project is used in the international evaluation forum REST-MEX 2022. You can access it at this link. https://sites.google.com/cicese.edu.mx/rest-mex-2022/registration

The data of this collection will be available here once the competition calendar has been completed, which can be consulted here. https://sites.google.com/cicese.edu.mx/rest-mex-2022/important-dates


# Epidemiological-Semaphore-Covid
The semaphore prediction consists of determining the Mexican Epidemiological Semaphore through the covid news in Mexico. The epidemiological semaphore, among other things, allows the activities for the tourism sector. It is a system of four ordered colors: red, orange, yellow, and green, where red is the most restrictive, and green is the most permissive. The color of the semaphore changes weekly and is independent in each state of the Mexican Republic. This color is determined by the government taking into account various factors such as the capacity of hospitals, the contagion and death curve, available ventilators, among others. Coincidentally, these factors are shared through the news of each state. If it is possible to predict the color of the epidemiological semaphore in advance, this will allow sellers and tourism service providers to take preventive measures. 


# Rest-mex 2022: Recommendation System for Text Mexican Tourism
#  Semaphore Covid Trainig Corpus
-*- coding: utf-8 -*-

## Spanish (Español)
El conjunto de datos se encuentra completamente en la carpeta training_news
El conjunto de datos consta de 94,540 Noticias agrupadas en 1912 instancias (el 70 % del conjunto de datos original. El otro 30 % será utilizado como conjunto de prueba). Cada instancia representa una semana de noticias referente a covid en alguno de los 32 estados de la República Mexicana. El nombre de cada instancia se representa con la siguiente expresión regular:

ID_News_COVID+Mexican+Region_colorW0_colorW2_colorW4_colorW8.txt

donde:

ID: es el identificador del archivo, el cual NO esta relacionado con temporalidad de los datos ni sus etiquetas.
Mexican+Region: Es el nombre del estado de México del que las noticias hacen referencia.
ColorWi: Es el color del semáforo epidemiológico después de i semanas. Los posibles valores son 'rojo', 'naranja', 'amarillo' y 'verde'.

Dentro de cada archivo txt, se encuentran hasta 50 noticias referentes a covid. Estas noticias fueron agrupadas ya que pertenecen a la misma semana natural (De lunes a domingo). Cada noticia inicia con el encabezado #START y termina con la etiqueta #END. 

##Importante 
Todos los participantes que se registraron al rest-mex 2022 y los que accedan a estos datos (sin importar que participen en el foro o no) aceptan utilizar los datos obtenidos del REST-MEX exclusivamente con fines académicos y de investigación. Cualquier otro uso de los datos será bajo su responsabilidad.

## English
The data set is located entirely in the folder training_news
The data set consists of 94,540 News items grouped into 1,912 instances (70% of the original data set. The other 30% will be used as a test set). Each instance represents a week of news regarding covid in one of the 32 states of the Mexican Republic. The name of each instance is represented as the following regular expression:

ID_News_COVID+Mexican+Region_colorW0_colorW2_colorW4_colorW8.txt

where:

ID: is the file identifier, which is NOT related to the temporality of the data or its labels.
Mexican+Region: It is the name of the state of Mexico that the news refer to.
ColorWi: It is the color of the epidemiological semaphore after i weeks. The possible values are 'rojo', 'naranja', 'amarillo' and 'verde'.

Within each txt file, there are up to 50 news items related to covid. These news were grouped as they belong to the same calendar week (Monday to Sunday). Each news starts with the header #START and ends with the tag #END.

##Important
All participants who registered to rest-mex 2022 and those who access this data (regardless of whether they participate in the forum or not) agree to use the data obtained from REST-MEX exclusively for academic and research purposes. Any other use of the data will be at your own risk.
