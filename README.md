# Тестовое задание Data Science
## Apple Price Prediction

Необходимо получить значения котировок акций компании Apple (AAPL, биржа NASDAQ), можно через выгрузку [финам](https://www.finam.ru/profile/akcii-usa-bats/apple-inc/export/) , и написать простенькую модель предсказания движения цены или вер-ть движения цены вверх или вниз за следующий период.

Котировка --- это текущая цена акции. В массивах данных обычно хранятся значения open (цена открытия в текущем таймфрейме), high (максимальная цена), low (минимальная цена), close (цена закрытия) и volume (объем сделок данного актива).

На вход программе подать не менее 2-х параметров (например, close и volume). Интервал котировок надо подобрать по наиболее приближенному результату: 1 мин, 5 мин, 10 мин, 15 мин, 30 мин, 1 час, 1 день.