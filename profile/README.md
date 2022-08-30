# Привет, это мы – разработчики Dodo Engineering

Тут мы открыто рассказываем про то, как создаём и развиваем IT в Dodo Brands (Додо Пицца, Дринкит, Донер 42), а также про ценности, принципы, бизнес-процессы, инструменты и правила жизни нашей команды.

[![http://dodo.dev/](https://github.com/dodopizza/RTFM/raw/master/images/header.png)](http://dodo.dev/)

> Мы приветствуем принцип **no bullshit**, поэтому если увидишь здесь информацию, которая покажется странной, неправильной и ты знаешь как лучше — смело присылай pull requests или пиши в личку @Schvepsss в любых соц. сетях (ну или почти любых).

# Коротко о команде Dodo Engineering

Наша команда появилась 22 апреля 2011 года в Сыктывкаре вместе с первой пиццерией Додо Пиццы. Тогда она состояла из двух разработчиков, которые создали сайт для заказа пиццы и заложили основу Dodo IS, нашей самописной системы. За это время мы сильно выросли. Сейчас система объединяет в себе функционал ERP+CRM+HRM и помогает франчайзи открывать бизнес «из коробки».

В 2017 году нас было 20, сейчас больше 200. 2019 год стал переломным: команда выросла больше чем в 3 раза, процессы поплыли, структура перестала работать эффективно. Мы начали перестройку и за полгода прошли путь от хаоса и разрухи до понятной структуры на 120+ человек и 18 команд. Будем дальше масштабироваться и теперь понимаем, как работает команда на 300 человек и будет работать на 500. Понимаем, какие задачи будут перед нами стоять, какую роль во всём этом играет распил монолита, куда можно расти разработчикам.

В 2020 году наш бизнес вырос – помимо Додо Пиццы запустили и развиваем кофейни Дринкит и донерные Донер 42. Планируем открытие новых стран. Мы как IT-команда продолжаем расти и масштабироваться вместе с бизнесом, решая проблему с помощью написания строчки кода и раскатки решения на все точки питания.

# Коротко в цифрах

| Мы | Цифры и знаки|
|:------------- |:---------------:|
| Всего сотрудников в компании | 500+ |
|IT-команда | 200+ |
|Количество пиццерий | 800+ |
|Количество донерных | 8|
|Количество кофеен | 5|
|Количество стран | 16 |
|Количество клиентов | 21 000 000+ |
|Максимальная нагрузка (заказов в минуту) | 370 |
|Стандартная нагрузка (заказов в минуту) | 250 |
|RPS | 3700 |
|Выручка в 2021 году (рублей) | 40 000 000 000 |

# Коротко о технологиях

* .NET 6:
  * ASP.NET Core в монолите – 16 сервисов;
  * ASP.NET Core вне монолита в k8s – 30 сервисов.
* на сайте React + TypeScript, в бекофисе мигрируем с jQuery, Angular первых версий тоже на React + TypeScript;
* 36 баз MySql на кластерах, кроме dev окружений;
* всё на Azure, с использованием RabbitMQ (местами Kafka, Azure Event Hubs), Kusto, CosmosDB, Redis и ещё много мелких радостей;
* все сервисы мы пишем на .NET, под Linux, запускаем в Kubernetes;
* детальный мониторинг на продакшене на базе Prometheus, сбор логов в Kusto, визуализация в Grafana, пейджер для дежурного в PagerDuty.

# 7 технологических радаров Dodo Engineering

1. [Infrastructure](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vT7Fr8ieNw34TIlxviFOhZQ1x7wFTS88kfK6loVoQIncEcF_xI2imNYNcMIQbLXGbkDKhfamLdPxZuh%2Fpub%3Fgid%3D1362144133%26single%3Dtrue%26output%3Dcsv%26format%3D%2FDodo+Engineering+Infra.csv).
2. [Backend](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vRJq9wMTAL7IWulP81qOyuAughwJ9NLMZy_jH4UibjVJF83rM_XdqdSTGWvIfvGS1PYV85LW5BVVUlv%2Fpub%3Fgid%3D1655424610%26single%3Dtrue%26output%3Dcsv%26format%3D%2FDodo+Engineering+Backend.csv).
3. [Frontend](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vQoFGOb7a0lQppQkYIKd1JQHFtp5dKGs8iX5INqy7avEV0Eh9EX3rEmDkUVhzfPMSLXFw-7qi1f2AMf%2Fpub%3Fgid%3D604704275%26single%3Dtrue%26output%3Dcsv%26format%3D%2FDodo+Engineering+Frontend.csv).
4. [QA](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vS3AzkgmCZ1ZzaN1XDnzJ_j6tax-l1w9idmWVoLIaadqh_4sqB8HnuGpdKBH4P8vQ_R0doeyuvZenxl%2Fpub%3Fgid%3D1718585886%26single%3Dtrue%26output%3Dcsv%26format%3D%2FDodo+Engineering+QA.csv).
5. [Data](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1AlBKLqQbfXnw4GOdcsnfmWDt8gpGyp2VuezmvnsLMTo%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BData.csv).
6. [iOS Dodo Pizza](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vTq1imTtTYF3hLOCr2SfmNNDyTQwu1Z29Nh6sQiCAkz-ADvenhFHPfzV82DXrHt4rsW3EIoMO_YqhU8%2Fpub%3Fgid%3D0%26single%3Dtrue%26output%3Dcsv%26format%3D%2FDodo+Pizza+iOS.csv).
7. [Android](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vRIJRCLRWKilMgx5rypHoCwGlUOpB79v4-oPPdSvNNSPkkgVao2uja2O4j1eEWqeUn34Ri0rzaNgut3%2Fpub%3Fgid%3D892813566%26single%3Dtrue%26output%3Dcsv%26format%3D%2FDodo+Engineering+Android.csv).

# Что ещё?

* Стратегия и правила жизни на корабле.
  * [Миссия, ценности, принципы](https://github.com/dodopizza/RTFM/blob/master/docs/our-mission.md).
* Как мы ведём разработку Dodo IS.
  * [Что такое Dodo IS](https://habr.com/ru/company/dododev/blog/506136/).
  * [Структура команды](https://github.com/dodopizza/RTFM/blob/master/docs/team-structure.md).
  * [Рыночные и глобальные команды](https://habr.com/ru/company/dododev/blog/666028/).
  * [Развитие и возможности в IT](https://github.com/dodopizza/RTFM/blob/master/docs/self-development.md).
  * [Onboarding](https://habr.com/ru/company/dododev/blog/510382/).
* Как стать частью нашей команды:
  * [Вакансии](https://dodo.dev/manager#jobs).
* [Где нас можно найти](https://github.com/dodopizza/RTFM/blob/master/docs/resource-links.md).
