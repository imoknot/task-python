# Вакансия :: Программист Python

Разработка бизнес-системы с использованием веб-технологий Автоматизация сервисов с большим количеством пользователей**(+)**

## От вас

### Обязательно

- Знание синтаксиса языка Python  **(+)**
- Опыт разработки на Python не менее 1 года **(+)**
- Базовые знания принципов работы Web **(+)**
- Желание работать в команде и развиваться **(+)**

### Приветствуется

- Навыки работы с Flask, Sanic (-) есть современные фреймворки умеющие работать асинхронно (aiohttp, fastapi etc) 
- Опыт работы с БД: PostgreSQL, MS SQL, MongoDB (+ Clickhouse, Tarantool, Redis, RethinkDB)
- Опыт разработки под ОС семейства GNU Linux **(+)**
- Работа с системами управления исходным кодом Git **(+)**
- Знания базовых принципов разработки (тестирование, рефакторинг, Code Review) **(+)**

### Будет круто, но не обязательно

- Знание английского языка на уровне чтения технической документации **(+)**
- Участие в разработке Open Source проектов **(+)** 
- Наличие профиля на GitHub, Stack Overflow https://github.com/imoknot/
- Наличие проектов которые можете продемонстрировать (- соглашение о неразглашении. Кратко - финтех. госуслуги. )
- Разработка с использованием TypeScript, знание современных frontend-библиотек и подходов к разработке (-)

## У нас

- Полный рабочий день, гибкий обед по желанию сотрудника, гибкое время начала рабочего дня **(+)**
- Полностью «белая» заработная плата с возможностью увеличения в процессе работы (зависит от отдачи сотрудника) **(+)**
- Добровольное медицинское страхование **(+)**
- Дружелюбная команда с юмором, готовая поддержать **(+)**
- Интересный проект и необычные задачи. Нет, если думаете, что рутины нет, она есть, но нацелены мы именно на продуктив
- Возможность одновременно участвовать в разных проектах и развивать другие компетенции (JS и все модное)
 **(-JS знаю. но не хочу))**
- Возможность попробовать современные тренды и практики в разработке ПО **(+)**
- По желанию: один день в неделю - удаленная работа (только удаленка)
- Никаких опенспейсов, а комфортное пространство в центре Тюмени **(+-)**
- Готовы безгранично делиться опытом при условии, что вы готовы принимать **(+)**

&nbsp;  

Если у вас есть опыт работы с 1С, то эта вакансия не для вас. Даже не пытайтесь. (опыт с 1С > 5 лет :( ) 
Если вакансия вас заинтересовала, но есть какие-то недопонимания и вопросы, приходите, обсудим, договоримся.(Удаленка)  
Большим плюсом будет выполнение тестового задания.**(+)**

## Тестовое задание

Решение принимается в виде PR к текущему проекту.

Есть несколько рабочих сервисов, у каждого сервиса есть состояние работает/не работает/работает нестабильно.

Требуется написать API который:

1. Получает и сохраняет данные: имя, состояние, описание
2. Выводит список сервисов с актуальным состоянием
3. По имени сервиса выдает историю изменения состояния и все данные по каждому состоянию

Дополнительным плюсом будет

1. По указанному интервалу выдается информация о том сколько не работал сервис и считать SLA в процентах до 3-й запятой

Вывод всех данных должен быть в формате JSON


####

1. create empty .env file, or create from example.env
2. docker-compose up -d --build
3. http://localhost:8099/docs for swagger documentation API 