## Tram Delays Analysis
### Description

**The aim is to investigate tram delays in Krakow, Poland**

### Files

The file ```Tram_Delays_Analysis.pdf``` includes analysis of tram delays. Steps of analysis that are included in the document are described in "Workflow" below.

The following files include analysis of tram delays using Python programming language for specific days between July 23, 2018 - July 31, 2018:
- ```Analysis_23-07-2018.ipynb```
- ```Analysis_24-07-2018.ipynb```
- ```Analysis_25-07-2018.ipynb```
- ```Analysis_26-07-2018.ipynb```
- ```Analysis_27-07-2018.ipynb```
- ```Analysis_30-07-2018.ipynb```
- ```Analysis_31-07-2018.ipynb```

### Workflow
1. Introduction
2. Data - assumption
3. Data - structure
4. Technology used
5. First part: thorough analysis for 7/23/2018 (Monday)
- verification of the number and length of delays for the analyzed tram lines
- distribution of delays throughout the day
- susceptibility of stops and tram lines to delays
- simple model presenting the general sense of using machine learning, on which delays can be predicted
6. Second part: comparative analysis for 7/23/2018 (Monday) - 7/31/2018 (Tuesday) excluding weekend
- verification of the number and length of delays for the analyzed tram lines
- distribution of delays throughout the day
- susceptibility of stops and tram lines to delays
- simple model presenting the general sense of using machine learning, on which delays can be predicted
7. Summary

### Conclusions
1. On average, about 43 trams appear on time
2. On average 89 trams arrive with a delay of max 2 min. It is also recommended to carry out an analysis outside the holidays
3. The greatest delays can be seen at stops away from the tram loop, when the tram route runs through the city center or intersects with traffic, and when the tram route is long
4. The smallest delays can be noted at stops close to the tram loop, when the tram route runs through the city center, has a separate tram lane and is relatively short
5. For some of the days analyzed, it is difficult to notice the tendency for the biggest delays to appear during peak hours (morning and afternoon), perhaps due to holidays
6. To achieve better results, it is worth analyzing the impact of the vehicle number (older vs. newer trains) and the dependence of the delay at a given stop taking into account the direction of travel (tram going from / to the loop)

### Article
Medium article can be found [here](https://medium.com/@anna.natalia.dutkiewicz/public-transport-always-late-or-exaggeration-39490d90c6f4)

### Acknowledgements
Books:
- Albon, Chris. 2018. Uczenie maszynowe w Pythonie. Receptury. Gliwice: Wydawnictwo Helion.
- Geron, Aurelien. 2018. Uczenie maszynowe z użyciem Scikit-Learn i TensorFlow. Gliwice: Wydawnictwo Helion.
- McKinney, Wes. 2018. Python w analizie danych. Gliwice: Wydawnictwo Helion.

Online courses:
- Brunner, Rene. Python fuer Data Science, Maschinelles Lernen & Visualization. Udemy.com
- **Vladimir Alekseichenko, Korona Wyzwań Uczenia Maszynowego, Data Workshop, https://dataworkshop.eu/challenge**

Online sources:
- https://aczepielik.github.io/post/kraktram/#regresja-kwantylowa
- https://github.com/aczepielik/KRKtram/tree/master/reports
- https://mateuszgrzyb.pl/3-najlepsze-sciagawki-z-bibliotek-python/
