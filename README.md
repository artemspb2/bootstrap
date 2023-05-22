# bootstrap

Пример бутстрап-анализа, учебный кейс, здесь для демонстрации навков

Выводы:
Надо разбираться с 5 "выбросами" - это ошибка при сборе данных или наша цель и желаемый результат? Желательно проверить появления выбросов в "генеральной совокупности", но тогда надо сравнивать не средние, а вероятность наличия этих выбросов в генеральной совокупности ( унас 5 выбросов в 500 наблюдениях, увеличивающее среднее, т.е. - это 99 процентиль).

Если цель задачи - исследовать различия, то т-тест показал неустойчивость к выбросам. Тест Манна-Уитни сработали "верно".

С бутстрэпом я понял, что надо дальше разбираться, лучше изучить его применение и код в питоне. Судя по уверениям лектора, бутстрэп будет полезен для определения вероятности наличия "выбросов" в генеральной совокупеости - т.е. 99 процентиля (5/500). Только надо еще понять как это сделать.

P.S. Хотя, конечно, понятно, что это сгенерированный датасет с искуственно добавленными 5 резко выделяющимися значениями, а не реальные данные.
