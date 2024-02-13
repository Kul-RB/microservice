# Задание
Предложите решение для обеспечения реализации API Gateway. Составьте сравнительную таблицу возможностей различных программных решений. На основе таблицы сделайте выбор решения.

Решение должно соответствовать следующим требованиям:
- маршрутизация запросов к нужному сервису на основе конфигурации,
- возможность проверки аутентификационной информации в запросах,
- обеспечение терминации HTTPS.

Обоснуйте свой выбор

# Решение
Требования | Kong Gateway | Tyk | KrakenD | Gravitee.io | Apinto Microservice Gateway | Apache APISIX 
---------- | ------------ | --- | ------- | ----------- | --------------------------- | -------------
Маршрутизация запросов к нужному сервису на основе конфигурации | + | + | + | + | + | +
Возможность проверки аутентификационной информации в запросах | + | + | + | + | + | +
обеспечение терминации HTTPS | + | + | + | + | + | +

Из 6 популярных API Gateway по данным требованиям подходят все, для выбора конкретного программного обеспечения необходимо более конкретно изучить предметную область, например если в организация не нуждается в JWT а хочет использовать API-key  или еще что нибудь, то KrakenD  не подходит для этого, также необходимо смотреть бенчмарки дял проверки потребления ресрсов и быстроты работы, также если в дальнейшем организация захочет перейти на Enterprise версию, так же необходимо смотреть какие из Gateway имеет такую возможность

# Задача
Составьте таблицу возможностей различных брокеров сообщений. На основе таблицы сделайте обоснованный выбор решения.

Решение должно соответствовать следующим требованиям:
- поддержка кластеризации для обеспечения надёжности,
- хранение сообщений на диске в процессе доставки,
- высокая скорость работы,
- поддержка различных форматов сообщений,
- разделение прав доступа к различным потокам сообщений,
- простота эксплуатации.

Обоснуйте свой выбор.

# Решение
Требования |  |  |  |  |  |  
---------- | ------------ | --- | ------- | ----------- | --------------------------- | -------------
 |  |  |  |  |  | 
 |  |  |  |  |  | 
 |  |  |  |  |  | 
