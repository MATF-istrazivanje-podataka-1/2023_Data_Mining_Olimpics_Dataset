## Analiza skupa podataka Olimpijske Igre

Autor: Marko Paunović 104/2020


Olimpijske igre su jedna od najznačajnijih sportskih manifestacija na svetu, događaj koji se održava na svake 4 godine i u kojem učestvuju hiljade sportista širom sveta takmičući se za medalje u različitim sportskim disciplinama.

Skup podataka Olympic Data možete naći na sajtu Kaggle pomoću linka: https://www.kaggle.com/datasets/bhanupratapbiswas/olympic-data

Ovaj skup sadrži podatke o takmičarima koji su se takmičili na Olimpijskim igrama u zadnjih 120 godina.
Ukupno ima 70 000 takmičara koji su opisani pomoću 15 atributa.
Cilj ovog projekta jeste sprovođenje detaljne analize podataka i, pomoću raznih tehnika, pravljenje optimalnih modela mašinskog učenja koji će nam pomoći da predvidimo da li će neki takmičar osvojiti medalju.

Dodatne biblioteke za rad: pandas, numpy, matplotlib, sklearn, seaborn, joblib.
Možete ih instalirati pokretanjem komande u terminalu: 
```pip install pandas numpy matplotlib sklearn seaborn joblib```


## Korišćeni alogiritmi:
Klasifikacija: DecisionTreeClasifier, RandomForestClasifier, KNeighborsClasifier
Klasterovanje: KMeans, BisectingKMeans, Agglomerative, DBSCAN
