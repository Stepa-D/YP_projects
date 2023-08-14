# YP_projects
Проекты, выполненные в рамках курса "Аналитик данных" Яндекс.Практикум.

| #  | Project Name | Industry  | Project objectives | Project description | Stack |
| ------------- | ------------- | ------------- | ------------------ | ------------- | ------------- |
| 1  | [Исследование объявлений о продаже квартир](1_real_estate_sales_analysis/1_real_estate_sales_analysis.ipynb)  | Online service | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | python, pandas, numpy, matplotlib, исследовательский анализ данных, визуализация данных, предобработка данных |
| 2  | [Исследование рынка компьютерных игр](2_video_games_sales_analisis/2_video_games_sales_analysis.ipynb) | Online store | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры  | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок. | python, pandas, numpy, scipy, matplotlib, seaborn, предобработка данных, исследовательский анализ данных, описательная статистика, проверка статистических гипотез |
| 3  | [Анализ бизнес-показателей развлекательного приложения Procrastinate Pro+](3_business_metrics_analysis/3_business_metrics_analysis.ipynb) | Internet Service | Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс. | Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным. | python, pandas, numpy, matplotlib, datetime, когортный анализ, юнит-экономика, продуктовые метрики |
| 4  | Принятие решений в бизнесе](4_decision_making/4_decision_making.ipynb) | Online shop | Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста. | python, pandas, numpy, datetime, scipy, matplotlib, A/B-тестирование, проверка статистических гипотез |
| 5  | [Событийная аналитика](projects_rus/6_mobile_grocery_app/mobile_grocery_app.ipynb) | Online shop | На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей. | python, pandas, numpy, scipy, plotly, datetime, math, событийная аналитика, продуктовые метрики, проверка статистических гипотез, визуализация данных |
| 7  | [Moscow food places](projects_rus/7_moscow_food_places/moscow_food_places.ipynb) | Catering market business | python, pandas, matplotlib, seaborn, plotly, folium |
| 8  | [Yandex Dzen Dashboard](projects_rus/8_yandex_dzen_dashboard/README.md) | Online Service | Tableau |
| 9  | [Game app monetization](projects_rus/9_final_project/9_1_game_app_monetization/game_app_monetization.ipynb) | Gamedev | python, pandas, numpy, scipy, matplotlib, seaborn, datetime |
| 10  | [A/B recommender system testing](projects_rus/9_final_project/9_2_recommender_system_test/ab_tests.ipynb) | Mobile App | python, pandas, numpy, scipy, math, datetime, matplotlib, seaborn, plotly, warnings |
| 11  | [Bookstore analysis](projects_rus/9_final_project/9_3_bookstore_analysis/sql.ipynb) | Offline business | python, pandas, SQLAlchemy, PostgreSQL |
