# Задача
Заказчик этого исследования — сеть отелей «Как в гостях». Необходимо разработать систему, которая сможет предсказывать отказ клиента от брони

**Цель:** чтобы привлечь клиентов, эта сеть отелей добавила на свой сайт возможность забронировать номер без предоплаты. Однако если клиент отменял бронирование, то компания терпела убытки. Сотрудники отеля могли, например, закупить продукты к приезду гостя или просто не успеть найти другого клиента.
Чтобы решить эту проблему, необходимо разработать систему, которая предсказывает отказ от брони. Если модель покажет, что бронь будет отменена, то клиенту предлагается внести депозит. Размер депозита — 80% от стоимости номера за одни сутки и затрат на разовую уборку. Деньги будут списаны со счёта клиента, если он всё же отменит бронь.

# Выводы
Лучшую модель для подсчета прибыли отеля основываясь на метрике кросс-валидации Recall победила модель "DecisionTreeClassifier". Её recall 0.659.
Отель до внедрения системы депозитов за 2017 год получил прибыль 32.43 млн. рублей. Отель при внедрении системы депозитов за 2017 год получил бы 
прибыль 44.47 млн. рублей. C учетом затрат на разработку системы депозитов, отель за год мог бы получить дополнительно 11,64 млн.рублей. 

# Стек технологий
Python, Pandas, Matplotlib, NumPy, Sklearn, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, StandardScaler, OneHotEncoder
