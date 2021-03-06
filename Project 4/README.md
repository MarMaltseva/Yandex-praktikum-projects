# Описание проекта "Анализ тарифов "Мегалайна""
## Данные
В распоряжении имеются данные 500 пользователей «Мегалайна», содержащие информацию об использовании тарифов за 2018 г.: 
- уникальный идентификатор пользователя
- имя пользователя
- фамилия пользователя
- возраст пользователя (годы)
- дата подключения тарифа (день, месяц, год)
- дата прекращения пользования тарифом (если значение пропущено, то тариф ещё действовал на момент выгрузки данных)
- город проживания пользователя
- название тарифного плана

- уникальный номер звонка
- дата звонка
- длительность звонка в минутах
- идентификатор пользователя, сделавшего звонок

- дата сообщения
- идентификатор пользователя, отправившего сообщение

- уникальный номер сессии
- объём потраченного за сессию интернет-трафика (в мегабайтах)
- дата интернет-сессии
- идентификатор пользователя
Также у нас есть информация о тарифах:
- название тарифа
- ежемесячная абонентская плата в рублях
- количество минут разговора в месяц, включённых в абонентскую плату
- количество сообщений в месяц, включённых в абонентскую плату
- объём интернет-трафика, включённого в абонентскую плату (в мегабайтах)
- стоимость минуты разговора сверх тарифного пакета (например, если в тарифе 100 минут разговора в месяц, то со 101 минуты будет взиматься плата)
- стоимость отправки сообщения сверх тарифного пакета
- стоимость дополнительного гигабайта интернет-трафика сверх тарифного пакета (1 гигабайт = 1024 мегабайта)
## Задача
Необходимо определить, какой тариф приносит большую прибыль для "Мегалайна", то есть проанализировать поведение клиентов и сделать вывод — какой тариф лучше.
## Инструменты
pandas, matplotlib.pyplot, scipy.stats, numpy
