# Crypto-Stock-portfolio-comparison
Comparison of two portfolios of cryptocurrencies and stocks, calculating their correlation, expected return, volatility (2020-2023), machine learning model (2020-2024)

Данная работа выполнялась в рамках научно-исследовательского семинара "Финансовые продукты и инвестиционные стратегии: разработка, анализ и управление рисками" в НИУ ВШЭ

Гипотеза:

За счет синергии с индексом NASDAQ портфель из компаний, которые связаны с криптовалютной индустрии, будут иметь большую доходность, чем портфель собранный из криптовалют

![image](https://github.com/gppoleshkin/Crypto-Stock-portfolio-comparison/assets/150899409/86074e13-e631-4986-a124-baab5310b851)


Цели работы:

Составить равновесные портфели из топ 5 криптовалют, на август 2020 года, и акицй компаний, которые были связаны с криптовалютной индустрии (т.е. занимались майнингом или просто держали криптовалюты на балансе на август 2020 года
Подсчитать и сравнить их доходность
Подсчитать их корреляцию

Этапы работы:

Обработка данных
Построение портфелей
Сравнение доходностей
Подсчет корреляции портфелей между собой и с индексой
Найти стандартное отклонение доходности и риск портфелей (VAR)
Бонус:

С помощью моделей машинного обучения построить прогноз доходностей портфелей на 2024 на год
Сравнить его с реальными данными

Итог работы:

Гипотеза оказалась подтвержденной

1) Фактическая доходность портфелей превышает их ожидаемую на рассматриваемом периоде (2020-2023)

2) Доходность портфелей положительно коррелирует между собой, оба портфеля коррелируют с индексом, но корреляция портфеля из акций более выражена

![image](https://github.com/gppoleshkin/Crypto-Stock-portfolio-comparison/assets/150899409/7d7ca45f-03e6-4327-872b-c1542f76194a)


3) По итогам расчета коэффициента Шарпа можно сказать, что портфель из криптовалют более эффективен, несмотря на то, что показал меньшую доходность на рассматриваемом периоде

Для портфеля криптовалют коэффициент Шарпа: 1.4036250728372592
Для портфеля аций коэффициент Шарпа: 1.073030373576763

4) Портфель из акций криптовалют показывает значительно большую волатильность, что делает его более рисковым

![image](https://github.com/gppoleshkin/Crypto-Stock-portfolio-comparison/assets/150899409/73da169b-e50a-432b-acf8-bc573ac4cf21)


5) Выбранные модели машинного обучения смогли спрогнозировать рост доходности, но не фактические значения

Отставание доходности портфеля криптовалют от портфеля акций можно объяснить тем, что из выбранных 5 криптовалют 2 значительно отставали в своем росте от общей капитализации криптовалютного рынка, BSV и BCH за прошедшие 4 года потеряли позиции в топ-5 криптовалют по капитализации

![image](https://github.com/gppoleshkin/Crypto-Stock-portfolio-comparison/assets/150899409/e7519422-0c94-4f55-8e58-4219a80dbf5c)

![image](https://github.com/gppoleshkin/Crypto-Stock-portfolio-comparison/assets/150899409/05a12abf-8685-4644-9502-cfdf7a4241ac)

