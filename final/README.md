# Задача
Оператор связи «ТелеДом» хочет бороться с оттоком клиентов

**Цель:** создать и обучить на представленных данных модель для прогноза оттока клиентов

# Выводы
Проведена работа с данными оператора связи «ТелеДом» который, хочет бороться с оттоком клиентов. Данные обработаны и подготовлены для обработки моделями. Изучали модели RandomForestClassifier, CatBoost и нейронную сеть. Две последних показали очень близкие результаты по качеству, а нейронная сеть оказалась значительно быстрее. Выиграла модель CatBoost. Дальнейшее тестирование показало: ROC-AUC на тестовой выборке = 0.83 и Accuracy на тестовой выборке = 0.79. Это очень хорошие показатели для модели. Так же полнота (Recall) = 89,4% и точность (Precision) = 83,65%, что тоже указывает на хорошее качество модели.

*Способы для дальнейшего улучшения модели*

-  Дополнительные данные: добавить данные.

-  Улучшение качества данных: устранение выбросов, обработка пропущенных значений и исправление ошибок.

-  Подбор гиперпараметров: осуществить поиск наилучших гиперпараметров для всех моделей.

-  Работа с признаками: убрать лишние / разработать новые / подобрать лучшие.

-  Использование других моделей: XGBoost, LightGBM. 

*Бизнес-рекомендации заказчику*

В целом, наибольший интерес для бизнеса представляют такие признаки как: MonthlyCharges (Расходы за месяц), Type (Тип оплаты: раз в год, два или ежемесячно), TotalCharges (Общие расходы абонента) и InternetService (Тип подключения). Они имеют наибольший вес при принятии решения клиентами. 

# Стек технологий
Python, Pandas, Matplotlib, Seaborn, NumPy, Sklearn, Psycopg2, StandardScaler, OneHotEncoder, GridSearchCV, CatBoost, RandomForestClassifier, Torch
