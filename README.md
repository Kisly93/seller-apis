## seller.py
Данный скрипт  позволяет управлять ценами и уровнями запасов товаров в вашем магазине на платформе [Ozon](https://ozon.ru/). 
Также скрипт скачивает информацию о доступности товаров из внешнего источника и обновляет уровни запасов в вашем магазине согласно этой информации.

### Назначение
Основная цель скрипта - автоматизировать обновление цен и запасов товаров в вашем магазине на платформе [Ozon](https://ozon.ru/).
Это позволит поддерживать актуальную информацию о наличии товаров, получаемую из внешнего источника, и корректировать цены на товары по необходимости.

### Как это работает
Загрузка списка товаров: Скрипт получает список товаров из вашего магазина на [Ozon](https://ozon.ru/) с помощью API.

Получение артикулов товаров: Скрипт получает артикулы товаров вашего магазина на основе полученного списка.

Обновление цен товаров: Скрипт обновляет цены на товары согласно информации из внешнего источника.

Обновление уровней запасов: Скрипт обновляет уровни запасов для каждого товара согласно информации из внешнего источника.


## market.py
Этот скрипт предназначен для автоматизации обновления остатков и цен товаров на [Яндекс Маркет](https://market.yandex.ru/). Он позволяет загружать информацию о товарах и их остатках, а также обновлять цены на товары в магазине на [Яндекс Маркет](https://market.yandex.ru/).

### Как это работает
Загрузка списка товаров: Скрипт получает список товаров из вашего магазина на [Яндекс Маркет](https://market.yandex.ru/) с помощью API.

Получение артикулов товаров: Скрипт получает артикулы товаров вашего магазина на основе полученного списка.

Обновление цен товаров: С помощью внешнего источника данных, скрипт обновляет цены на товары.

Обновление уровней запасов: Используя данные из внешнего источника, скрипт обновляет уровни запасов для каждого товара.