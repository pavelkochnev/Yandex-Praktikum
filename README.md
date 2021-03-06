# Репозиторий работ из курса "Специалист по Data Science"


Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме по профессии "Специалист по Data Science". Первые четыре проекта - аналитические. Эти проекты намернно выполнены без использования алгоритмов машинного обучения. Все остальные проекты используют машинное обучение.

|№| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| 1| [Исследование надежности заемщиков](Research_on_the_reliability_of_borrowers) | Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга.| *pandas, pymystem3* |
| 2| [Исследование объявлений о продаже квартир](Research_of_ads_for_the_sale_of_apartments) | Доступен архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Задача — установить параметры влияющие на рыночную стоимость объектов недвижимости. В последствии это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.| *pandas* |
| 3| [Определение перспективного тарифа для телеком компании](Tariff_determination_for_telecom_company) | Клиентам федерального оператора сотовой связи предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов.| *pandas, numpy, scipy* |
| 4| [Выявление закономерностей определяющих успешность компьютерной игры](Identification_of_patterns_that_determine_the_success_of_a_computer_game) | Интернет-магазину, который продаёт по всему миру компьютерные игры, нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.| *pandas, numpy, scipy* |
| 5| [Рекомендация тарифов](Tariffs_recommendation) | Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». Необходимо построить модель со значением accuracy не менее 0.75.| *pandas, sklearn, catboost, tqdm* |
| 6| [Прогнозирование оттока клиентов банка](Bank_customer_churn_modeling) | Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Необходимо построить модель со значением F1-меры не менее 0.59.| *pandas, numpy, sklearn, catboost, tqdm* |
| 7| [Выбор локации для нефтяной скважины](Location_selection_for_oil_well) | Предоставлены данные по пробам нефти в трёх регионах. Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль.| *pandas, numpy, sklearn* |
| 8| [Предсказание коэффициента восстановления золота](Gold_recovery_rate_prediction) | Необходимо подготовить прототип модели машинного обучения. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В распоряжении имеются данные с параметрами добычи и очистки.| *pandas, numpy, sklearn, catboost, tqdm* |
| 9| [Защита пользовательских данных путем их преобразования](User_data_protection) | Необходимо разработать такой метод преобразования данных клиентов страховой компании, чтобы по ним было сложно восстановить персональную информацию. Нужно защитить данные таким образом, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.| *pandas, numpy, sklearn, catboost, tqdm* |
|10| [Оценка рыночной стоимости автомобиля на основе исторических данных](Estimating_the_market_value_of_a_car_based_on_historical_data) | Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Нужно построить модель для определения стоимости.| *pandas, numpy, lightgbm, catboost, sklearn* |
