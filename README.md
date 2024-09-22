# hw_9_ml_flask

Стек:
ML: sklearn, pandas, numpy
API: flask 
Запросы: requests
Данные: с kaggle - https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction
Модель: RandomForestRegressor
Задача: Предсказать стоимость дома на основе имеющихся признаков.Задача регрессии.

Используемые признаки:
longitude - Мера того, насколько западнее находится дом; чем больше значение, тем западнее.

latitude - Мера того, насколько севернее находится дом; чем больше значение, тем севернее.

housing_median_age - Средний возраст дома.

total_rooms - Общее количество комнат.

total_bedrooms - Общее количество спален.

population -  Общее количество людей

households - Общее количество домохозяйств

median_income - Средний доход домохозяйств

ocean_proximity - Расположение дома относительно океана/моря.

Клонируем репозиторий, переходим в директорию server и запускаю наш бэкенд.

`git clone`

`cd app/server`

`python run_server.py`

