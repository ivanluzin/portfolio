# Прогнозирование дохода от нефтедобычи в различных регионах
## Цель проекта
Выбрать наиболее выгодный район для нефтедобычи из трех представленных. Спрогнозировать доверительный интервал прибыли и риск убытков техникой Bootstrap.
## Данные
Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. 
## Стек
 `pandas` `matplotlib` `seaborn` `sklearn` `numpy` `scipy` `Машинное обучение` `Регрессия` `Bootstrap` `Бизнес-модель`
## Что сделано
Выполнен исследовательский анализ данных. Для каждого из трех районов обучена модель линейной регрессии и спрогнозированы запасы нефти в скважинах. Бутстрэпом отобраны по 500 скважин 1000 раз в каждом регионе случайным образом. В каждом же регионе 1000 раз спрогнозирована прибыль от добычи нефти в 200 лучших скважинах из 500 отобранных, после чего выполнен расчет 95%-го доверительного интервала и риск убытков.
## Вывод
Для нефтедобычи выбран второй регион, так как в нем, несмотря на меньший объем запасов, гораздо ниже риски убытков и выше средняя прибыль. Стоит отметить, что средняя прибыль во втором регионе на уровне с первым и третьим регионами обусловлена, скорее всего, плохой предсказательной способностью моделей, обученных на данных первого и третьего региона. Это означает, что в первом и третьем регионе стоит рассмотреть другие модели машинного обучения, чтобы повысить качество прогноза.