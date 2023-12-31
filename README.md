# bootstrap-petroleum-boreholes-analysis

**Нужно выбрать лучший регион для добычи нефти.**
# Цель проекта
Построить модель для определения региона, где добыча нефти принесёт наибольшую прибыль. Провести анализ возможной прибыли и рисков техникой Bootstrap.
# Про данные
Доступно три региона, в каждом из которых сделали по 100000 скважин и взяли из них пробы.
### Описание данных:
**geo_data_0.csv, geo_data_1.csv, geo_data_2.csv**
---
**id —** уникальный идентификатор скважины;

**f0, f1, f2 —** три признака скважин;

**product —** объём запасов в скважине (тыс. баррелей).
## Важные условия
* Для обучения модели подходит только линейная регрессия.

* При разведке региона исследуют 500 точек, из которых с помощью машинного обучения выбирают 200 лучших для разработки.

* Бюджет на разработку скважин в регионе — 10 млрд рублей.

* Один баррель сырья приносит 450 рублей дохода. Доход с каждой единицы продукта составляет 450 тыс. рублей, поскольку объём указан в тысячах баррелей.

* У выбранного региона вероятность убытков должна быть меньше 2.5%.
