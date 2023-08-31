Ниже представлены реализованные мной проекты

| Проект | Описание | Используемые методы и библиотеки |
| :-------| :-----------|:-----------|
| [Предсказание стоимости жилья](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Предсказание%20стоимости%20жилья.ipynb) | В проекте обучается модель линейной регрессии на данных о жилье в Калифорнии в 1990 году.Обучим модель и сделаем предсказания на тестовой выборке. Для оценки качества модели используем метрики RMSE, MAE и R2. Помимо этого соберем всю цепочку обработки фичей в пайплайн, прогоним все это через gridsearch и посмотрим значение метрик на кросс-валдиации. |`pyspark`, `pandas`, `numpy`, `seaborn`, `pipeline`, `crossvalidator`, `paramgridbuilder`|
| [Предсказание стоимости авто на вторичном рынке](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Предсказание%20стоимости%20авто%20на%20вторичном%20рынке.ipynb) | Целью проекта является разработанная модель предсказания стоимости автомобиля на вторичном рынке. В проекте используется техника построения пайплайнов и нахождение гиперпараметров моделей используя фреймворк Optuna.|`pandas`, `numpy`, `seaborn`, `sklearn`, `catboost`, `optuna`, `pipeline`|
| [Прогнозирование оттока клиентов в отеле](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Прогнозирование%20оттока%20клиентов%20в%20отеле.ipynb) | Нужно разработать систему, которая предсказывает отказ клиента от брони. Это поможет отелю снизить убытки путем удержания депозита за однц ночь.|`pandas`, `numpy`, `seaborn`, `sklearn`|
| [Выбор локации для скважины](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Выбор%20локации%20для%20скважины.ipynb) | Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Нужно построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Также проанализировать возможную прибыль и риски техникой Bootstrap.|`pandas`, `numpy`, `scipy`, `seaborn`, `matplotlib`,  `sklearn`|
| [Построение модели предсказания ухода клиента](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Построение%20модели%20предсказания%20ухода%20клиента.ipynb) | Из банка стали уходить клиенты. Каждый месяц. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.|`pandas`, `numpy`, `seaborn`, `matplotlib`, `sklearn`|
| [Статистический анализ данных пользователей мобильной связи](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Статистический%20анализ%20данных%20пользователей%20мобильной%20связи.ipynb) | Телеком компания предлагает клиентам два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Проводим анализ тарифов на небольшой выборке клиентов. Анализ поведения клиентов и пытаемся сделать вывод — какой тариф лучше.|`pandas`, `numpy`, `scipy`, `seaborn`, `matplotlib`|
| [Рекомендация тарифов](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Рекомендация%20тарифов.ipynb) | Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». В нашем распоряжении данные о поведении клиентов. Нужно построить модель для задачи классификации, которая выберет подходящий тариф.|`pandas`, `numpy`, `seaborn`, `matplotlib`, `sklearn`|
| [Исследование объявлений о продаже квартир](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Исследование%20объявлений%20о%20продаже%20квартир.ipynb) | Исследование данных сервиса Яндекс.Недвижимость — архива объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Определение рыночной стоимости объектов недвижимости.|`pandas`, `pymystem3`|
| [Исследование данных о российском кинопрокате](https://github.com/GrigoriyAkhmetshakirov/Projects/blob/main/Исследование%20данных%20о%20российском%20кинопрокате.ipynb) | Изучение рынка российского кинопроката. Исследование фильмов, которые получили государственную поддержку, пытаемся ответить на вопрос, насколько такие фильмы интересны зрителю.|`pandas`|



