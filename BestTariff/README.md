# Определение перспективного тарифа для телеком-компании 

## Данные:  

*Таблица 1(информация о пользователях):*
- уникальный идентификатор пользователя
- имя пользователя
- фамилия пользователя
- возраст пользователя (годы)
- дата подключения тарифа (день, месяц, год)
- дата прекращения пользования тарифом (если значение пропущено, то тариф ещё действовал на момент выгрузки данных)
- город проживания пользователя
- название тарифного плана

*Таблица 2 (информация о звонках):*
- уникальный номер звонка
- дата звонка
- длительность звонка в минутах
- идентификатор пользователя, сделавшего звонок

*Таблица messages (информация о сообщениях):*
- уникальный номер сообщения
- дата сообщения
- идентификатор пользователя, отправившего сообщение

*Таблица 3(информация об интернет-сессиях):*
- уникальный номер сессии
- объём потраченного за сессию интернет-трафика (в мегабайтах)
- дата интернет-сессии
- идентификатор пользователя

*Таблица 4(информация о тарифах):*
- название тарифа
- ежемесячная абонентская плата в рублях
- количество минут разговора в месяц, включённых в абонентскую плату
- количество сообщений в месяц, включённых в абонентскую плату
- объём интернет-трафика, включённого в абонентскую плату (в мегабайтах)
- стоимость минуты разговора сверх тарифного пакета (например, если в тарифе 100 минут разговора в месяц, то со 101 минуты будет взиматься плата)
- стоимость отправки сообщения сверх тарифного пакета
- стоимость дополнительного гигабайта интернет-трафика сверх тарифного пакета (1 гигабайт = 1024 мегабайта)

## Задачи
Клиентам федерального оператора сотовой связи предлагают два тарифных плана: «Смарт» и «Ультра». 
Необходимо провести предварительный анализ тарифов на небольшой выборке клиентов и сделать вывод о том, какой тариф более прибыльный.

## Используемые библиотеки:  

*pandas, scipy, numpy, math, matplotlib*

