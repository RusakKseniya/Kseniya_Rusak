# Статистический анализ данных сервиса аренда самокатов Go Fast

## Описание
Являясь аналитиком популярного сервиса аренды самокатов GoFast необходимо проанализировать данные о некоторых пользователях из нескольких городов, а также об их поездках. А  также проверить некоторые гипотезы, которые могут помочь бизнесу вырасти.
Чтобы совершать поездки по городу, пользователи сервиса GoFast пользуются мобильным приложением. Сервисом можно пользоваться:
 - без подписки
    - абонентская плата отсутствует;
    - стоимость одной минуты поездки — 8 рублей;
    - стоимость старта (начала поездки) — 50 рублей;
- с подпиской Ultra
    - абонентская плата — 199 рублей в месяц;
    - стоимость одной минуты поездки — 6 рублей;
    - стоимость старта — бесплатно.

## Данные
Исследование проводится на наборе данных  сервиса аренды самокатов Go Fast. Данные предоставлены в трех датасетах и содержат следующую информацию: 

1. Пользователи — users_go.csv
    - user_id (уникальный идентификатор пользователя);
    - name (имя пользователя);
    - age (возраст);
    - city (город);
    - subscription_type (тип подписки free, ultra).  

2. Поездки — rides_go.csv  
    - user_id (уникальный идентификатор пользователя);
    - distance (расстояние, которое пользователь проехал в текущей сессии (в метрах));
    - duration (продолжительность сессии (в минутах) — время с того момента, как пользователь нажал кнопку «Начать поездку» до момента, как он нажал кнопку «Завершить поездку»);
    - date (дата совершения поездки).  

3. Подписки — subscriptions_go.csv
    - subscription_type	(тип подписки);
    - minute_price (стоимость одной минуты поездки по данной подписке);
    - start_ride_price (стоимость начала поездки);
    - subscription_fee (стоимость ежемесячного платежа).

## Цель
Исследование направлено на изучение поведения пользователей сервиса, c целью выявления закономерностей которые позволят увеличить количество пользователей с подпиской.

## Задачи
1. Провести предварительный анализ данных для понимания их структуры и полноты.
2. Обработать и очистить данные от выбросов и недостающих значений, чтобы обеспечить корректность последующих анализов.  
3. Исследовать данные о поведении пользователей и их поездках.  
4. Провести проверку гипотез для увеличения числа пользователей c подпиской при помощи акций.  
5. Сделать общий вывод на основании проведенного исследования и дать рекомендации заказчику.

## Навыки и инструменты
Pandas, Matplotlib, Seaborn, Numpy, SkiPy, описательная статистика, распределения, проверка гипотез, исследовательский анализ данных, визуализация данных, предобработка данных.

