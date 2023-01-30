# Meteorites-landings
Ce Projet présente une analyse quantitative des chutes de météorites.

## Statistiques descriptives 
![image](https://user-images.githubusercontent.com/123311478/215516447-a81d96c9-7d47-4e41-9409-13b4592c33b9.png)
La moyenne de 1.868596e+04 kg indique que la valeur centrale des masses des météorites dans la base de données est d'environ 18 685,96 kg. Cepandant, la moyenne est influencée par des valeurs extrêmement élevées (valeurs aberrantes) et elle ne refléte donc pas la réalité de la plupart des météorites dans la base de données. On conclut cela en regardant la masse maximum qui est de 60 000 000 kg, et en analysant l'écart type qui nous indique que les valeurs de masses des météorites varient avec un écart de 689 498,1 kg.

La médianne de 3.015000e+01 kg indique que la valeur centrale dans cette base de donnée est de 30.15 kg. On la considère comme une mesure de tendance plus robuste que la moyenne car elle ne peut pas être influencée par les valeurs aberrantes.

Le premier quartile de 6.550000e+00 kg indique que 25% des météorites ont une masse inférieure ou égale à 6.55 kg. Cela montre que la plupart des météorites ont une masse relativement faible.


## Correlation
![image](https://user-images.githubusercontent.com/123311478/215516615-bd45de46-b582-4c13-a3bd-874c2acee2c0.png)
La corrélation entre mass et year est de -0.124224, ce qui signifie qu'il existe une relation faiblement négative entre la masse des météorites et l'année de leur chute. Cela signifie que, dans l'ensemble, les météorites les plus lourdes sont tombées il y a plus longtemps.

La corrélation entre mass et reclat est de 0.036313, ce qui signifie qu'il existe une relation faiblement positive entre la masse des météorites et leur latitude de chute. Cela signifie qu'il y a une légère tendance à ce que les météorites les plus lourdes tombent plus près des pôles.

La corrélation entre mass et reclong est de -0.027074, ce qui signifie qu'il existe une relation faiblement négative entre la masse des météorites et leur longitude de chute. Cela signifie qu'il y a une légère tendance à ce que les météorites les plus lourdes tombent plus près des méridiens de longitude.

## Analyse des graphiques 

### Graphe 1
![image](https://user-images.githubusercontent.com/123311478/215517033-1626be6a-60fa-4052-af80-7e3885c62759.png)
Le premier graphique est un histogramme qui montre la distribution des masses des météorites inférieures à 200. Il est clair qu'il y a une très forte densité de météorites dont la masse est comprise entre 0g et 10g, avec un pic d'environ 1750 météorites enregistrées dans cette plage de masses. Cependant, cette densité diminue rapidement pour les masses plus élevées.
### Graphe 2
![image](https://user-images.githubusercontent.com/123311478/215517155-02a5c745-7af1-4a65-9abc-8e19559b8e99.png)

le 2eme graphique est une boîte à moustache, en regardant ses résultats, on peut observer que :

La médiane est autour de 14 indique que la valeur centrale des masses des météorites est d'environ 14 grammes. Le premier quartile est autour de 4 indique que 25% des météorites ont une masse inférieure ou égale à 4.1 grammes. Le quartile supérieur 45 indique que 75% des météorites ont une masse inférieure ou égale à 45.4 grammes. Les valeurs extrêmes (110 à 200) indiquent qu'il y a plusieurs météorites qui ont une masse extrêmement élevée, qui peut être considérée comme une valeur aberrante. Il est important de noter que ces valeurs aberrantes peuvent avoir un impact important sur les statistiques globales, comme la moyenne ou l'écart type, et peut fausser l'interprétation des données. Il est donc important de prendre en compte ces valeurs lors de l'analyse des données.

En utilisant des techniques statistiques plus avancées, il serait possible de modéliser la distribution des masses des météorites et d'estimer les probabilités associées à chaque valeur de la masse des météorites. Cela pourrait permettre de comprendre mieux comment la masse des météorites est distribuée dans la population étudiée, ainsi que les facteurs qui influencent cette distribution.

### Graphe 3
![image](https://user-images.githubusercontent.com/123311478/215517280-7a44540f-2e5c-48cd-bf6f-11048b4c84fa.png)
Le 3ème graphe permet de visualiser la répartition des météorites à travers le monde. Les résultats montrent une faible densité de météorites dans les régions polaires, ce qui est en accord avec les résultats précedemment trouvé en utilisant les correlations. Ces observations sont également en accord avec les tendances générales de la distribution des météorites sur la surface terrestre. Les résultats de cette analyse peuvent contribuer à une meilleure compréhension des processus géologiques et météorologiques impliqués dans la trajectoire et l'impact des météorites sur la terre.
