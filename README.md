# Проекты по курсу Яндекс.Практикум "Специалист по DataScience"

## Модули
Модуль 1:
- [Спринт 01. Предобработка данных](#спринт-01)
- [Спринт 02. Исследовательский анализ данных](#спринт-02)
- [Спринт 03. Статистический анализ данных](#спринт-03)
- [Спринт 04. Сборный проект](#спринт-04)


Модуль 2:
- [Спринт 05. Введение в машинное обучение](#спринт-05)
- [Спринт 06. Обучение с учителем](#спринт-06)
- [Спринт 07. Машинное обучение в бизнесе](#спринт-07)
- [Спринт 08. Сборный проект](#спринт-08)



## Спринты
### Спринт 01
**Предобработка данных. Проект по исследованию надежности заемщиков.**
- Цель и задача: Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
- Описание: Предобработка данных. Выделение категорий. Подготовка сводных таблицы с долями просроченных задолженностей по категориям клиентов.  
- Tags: pandas, предобработка данных, лемматизация, pivot-таблицы


### Спринт 02
**Исследовательский анализ данных. Проект по исследованию рынка недвижимости Санкт-Петербурга и Ленинградской области.**
- Цель и задача: Целью исследования является изучение объявлений о продаже жилья в Санкт-Петербурге и области и определение на их основе параметров, определяющих рыночную стоимость объектов недвижимости. В распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. 
- Описание: Предобработка данных, подготовка расчетных признаков, выделение сегментов рынка. Исследование времени продаж и факторов, определяющих стоимость. Оценка распределения основных параметров квартир по сегментам.
- Tags: pandas, matplotlib, plotly, предобработка данных, pivot-таблицы, boxplot


### Спринт 03
**Статистический анализ данных. Проект по определению перспективного тарифа для телеком компании.**
- Цель и задача: Исследование проводится с целью оценки прибыльности двух тарифных планов: «Смарт» и «Ультра» - и последующей подготовки рекомендаций коммерческому департаменту по корректировке рекламного бюджета. Исследование проводится на небольшой выборке клиентов - 500 абонентов «Мегалайн» из разных городов РФ. В отношении абонентов предоставлена следующая информация: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Цель - проанализировать поведение клиентов и сделать вывод — какой тариф лучше. 
- Описание: Подготовка сводных таблиц объема и стоимости оказанных услуг связи. Поиск аномалий. Проверка статистических гипотез о средней выручке абонентов различных тарифов и регионов.
- Tags: pandas, plotly, предобработка данных, pivot-таблицы, t-test, subplot


### Спринт 04
**Сборный проект модуля 1. Выявление факторов, определяющих успешность компьютерных игр, и прогнозирование продаж на 2017 год.**
- Цель и задача: Исследование проводится на основе исторических данных из открытых источников о продажах игр, оценках пользователей и экспертов, жанрах и платформах (например, Xbox или PlayStation). Данные представлены за период до 2016 года (за 2016 год - данные неполные). Цель исследования - выявить определяющие успешность игры закономерности, что позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании на 2017 год.
- Описание: Выявление закономерностей по жанрам и регионам. Определение акутального периода для прогнозирования. Выявление текущих трендов. Оценка корреляции рейтингов  и коммерческого успеха игр. Поиск аномалий. Проверка статистических гипотез о пользовательских рейтингах.
- Tags: pandas, plotly, предобработка данных, pivot-таблицы, t-test, subplot, интерактивные графики

---------------------------------------------------------------------------------------------------
### Спринт 05
**Введение в машинное обучение. Рекомендация тарифных планов на основе данных о поведении клиентов.**
- Цель и задача: Построение модели для задачи классификации, которая выбирает один из двух тарифов оператора «Мегалайн»: «Смарт» и «Ультра», на основе данных о поведении клиентов, которые уже перешли на эти тарифы. 
- Описание: Задача классификации. Оценка корреляций. Разделение данных на train/valid/test. Обучение моделей, проверка на адекватность.
- Tags: pandas, plotly, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, dummy, accuracy


### Спринт 06
**Обучение с учителем. Прогнозирование оттока клиентов.**
- Цель и задача: Построить модель для прогнозирования, уйдёт клиент из банка в ближайшее время или нет. В распоряжении исторические данные о поведении клиентов и расторжении договоров с банком. Целевая метрика - F1-меры не менее 0.59.
- Описание: Задача классификации. Оценка корреляций и поиск аномалий. Подготовка Pipeline. Обучение моделей с подбором гиперпараметров, проверка на адекватность. Балансировка целевых классов. График ROC-AUC, настройка порогов отнесения к целевым классам. Оценка значимости обучающих признаков. 3D-куб перебора гиперпараметров.
- Tags: pandas, plotly, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, dummy, pipeline, gridsearch, cross-validation, roc-auc, f1, precision, recall


### Спринт 07
**Машинное обучение в бизнесе. Выбор локации для скважины.**
- Цель и задача: Основная задача исследования - построение модели машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Анализ возможной прибыли и рисков должен выполняться с применением техники Bootstrap. На исследование предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.  
- Описание: Задача регрессии. Оценка корреляций и распределений анонимных признаков. Подготовка Pipeline. Стандартизация и кодирование признаков. Обучение моделей с подбором гиперпараметров. Оценка значимости обучающих признаков. Bootstrap и построение доверительных интервалов.
- Tags: pandas, plotly, LinearRegression, pipeline, gridsearch, cross-validation, rmse



