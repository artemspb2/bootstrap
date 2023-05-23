# bootstrap

Пример бутстрап-анализа, учебный кейс, здесь для демонстрации навыков/An example of bootstrap analysis, a training case, here for a skills demonstration (comment in English below)

Выводы:
Надо разбираться с 5 "выбросами" - это ошибка при сборе данных или наша цель и желаемый результат? Желательно проверить появления выбросов в "генеральной совокупности", но тогда надо сравнивать не средние, а вероятность наличия этих выбросов в генеральной совокупности ( унас 5 выбросов в 500 наблюдениях, увеличивающее среднее, т.е. - это 99 процентиль).

Если цель задачи - исследовать различия, то т-тест показал неустойчивость к выбросам. Тест Манна-Уитни сработали "верно".

С бутстрэпом я понял, что надо дальше разбираться, лучше изучить его применение и код в питоне. Судя по уверениям лектора, бутстрэп будет полезен для определения вероятности наличия "выбросов" в генеральной совокупеости - т.е. 99 процентиля (5/500). Только надо еще понять как это сделать.

P.S. Хотя, конечно, понятно, что это сгенерированный датасет с искуственно добавленными 5 резко выделяющимися значениями, а не реальные данные.


Conclusions:
We need to deal with the 5 "outliers" - is this a data collection error or our goal and desired result? It is desirable to check the occurrence of outliers in the "general population", but then we should not compare averages, but the probability of these outliers in the general population (we have 5 outliers in 500 observations, increasing the mean, i.e. - it is the 99th percentile).

If the goal of the problem is to examine differences, then the t-test has shown to be unstable to outliers. The Mann-Whitney test worked "correctly."

With the bootstrap, I realized that I need to further understand, better study its application and code in python. According to the assurance of the lecturer, bootstrap will be useful to determine the probability of the presence of "outliers" in the general population - i.e. 99th percentile (5/500). We just have to figure out how to do it.

P.S. Although, of course, it is clear that this is a generated dataset with artificially added 5 sharply distinguished values, rather than real data.
