COVINFORM -> Google covid 19 open data -> datos en españa: https://www.sanidad.gob.es/profesionales/saludPublica/ccayes/alertasActual/nCov/vacunaCovid19.htm no son datos específicos de tipo vacuna, pero tiene sentido incluir como priori

CORD-19 -> Este es uno de los buscadores que mejor funciona con el corpus; https://cord19.vespa.ai/search?query=UCI+mortality+prediction. Articulo encontrado interesante en el propio buscador: https://cord19.vespa.ai/article/159237

https://as.com/diarioas/2022/01/17/actualidad/1642416944_729602.html: El articulo referencia a este proyecto, https://www.ciberes.org/sala-de-prensa/ciberesucicovid. Dentro de este se encuentran algunos artículos como "The evolution of the ventilatory ratio is a prognostic factor in mechanically ventilated COVID-19 ARDS patients", que puede tener información relevante para responder algunas de las preguntas.

https://cuidateplus.marca.com/bienestar/2020/09/29/conoce-secuelas-coronavirus-covid-19-persistente-175029.html -> El estudio contiene información interesante para responder preguntas sobre el Covid persistente, empezando por una definición clara de secuelas.

https://www.madrimasd.org/notiweb/noticias/un-estudio-clasifica-gravedad-covid-segun-los-sintomas-permitira-predecir-quien-se-pondra-mejor-o-peor -> El estudio mencionado remarca la existencia de 4 grupos fenotípicos, que ya se mencionaba en el TFM del otro chico.

https://www.mdpi.com/2077-0383/9/6/1733 -> puede contener información relevante, pero más bien para la primera ola, teniendo en cuenta las fechas.

https://www.covidanalytics.io/mortality_calculator -> El objetivo es similar al del TFM; lo mismo se puede decir del otro: https://wp.bcamath.org/news/es/2021/01/27/pronostico-precoz-de-las-infecciones-de-covid-19-a-traves-de-machine-learning/, aunque no viene con un paper incluido (tengo que revisar eso).

https://thorax.bmj.com/content/76/9/920?fbclid=IwAR2ZwyFzDAB4stl0M3w9a5AMOgApaI8CqbdwO_VzD1LJmQKjF2yNRd_Zzfo&int_source=trendmd&int_campaign=usage-042019&int_medium=cpc -> el paper incluye variables de gravedad y puede servir para justificar una selección de atributos, pero quizás no tanto con las olas más recientes.

En zenodo he encontrado dos papers interesantes: https://zenodo.org/record/5856318#.YgQEUozMLJw, https://zenodo.org/record/4686707#.YgQEhIzMLJw

https://reader.elsevier.com/reader/sd/pii/S2666521221000065?token=469186D8F75A8F8833BEC5C6682EAB38D2F539F2172F40B111FCCF9286A8970776A7794FC17486193DA54DD130953D9E&originRegion=eu-west-1&originCreation=20220209210253 -> El trabajo es efectivamente similar a otros ya planteados y aunque es un modelo desarrollado para la primera ola, estaría bien explotar las ideas mostradas en el paper (ensemble de lr) con datos más recientes.

https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(21)00799-6/fulltext -> Para el uso buscado quizás una regresión logística multinivel empieza a ser complicada de entender para el personal sanitario. Como mínimo se pueden estudiar los resultados del estudio para selección de variables y validación de hipótesis.

https://espanol.medscape.com/verarticulo/5907437 -> Es muy útil tener esta definición para tener algo que citar en la memoria.

https://www.medrxiv.org/content/10.1101/2021.10.18.21265168v1 -> Este estudio usa xgboost, que lanza preguntas sobre si vale la pena utilizar un modelo menos interpretable pero con mayor precisión.