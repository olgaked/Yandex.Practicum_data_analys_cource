## Проект
Выделение групп пользователей мобильного приложения на основе поведения

## Цель проекта

регулярный анализ в целях контроля вовлеченности пользователей, 
выдвижение гипотез о способах оптимизации путей пользователей, 
выдвижение гипотез для экспериментов

## Результат исследования
Источник пользователей влияет на конверсию, а добавление пользователем объявления в избранное, не влияет на удержание.

## Используемые библиотеки

pandas, numpy, seaborn, matplotlib.pyplot, stats, datetime, plotly.express, warnings

## Статус

исследование завершено

## Источник информации 

выгрузка логов событий в приложении, информация об источние для каждого пользователя.

## Описание проекта

Было проведено уточнение запроса заказчика, декомпозиция задачи.

В рамках проекта была проведена предобработка данных: переименованы столбцы, измененны типы данных. Аномалий не обнаружено. Пропусков и дубликатов нет. Были стандартизированы названия событий.

В ходе исследовательского анализа данных изучены период анализа, общее число событий и польщователей. Было рассмотренно распределение событий по пользователям. Была определена длина сессии и выделены сессии. Рассмотренно распределение событий во времени. Была изучена зависимость числа целевых событий от числа прочих событий. Были сегментированы пользователи в зависимости от средней длительности сессии и количества сессий в анализируемый период.

Были изучены метрики конверсии, удержания, числа событий и длительности сессий в разрезе групп. Проанализировано отличие в длительности между событиями для пользователей, пришедших в приложение в разные недели анализируемого периода.

Были сформулированы статистические гипотезы и проведены статистические тесты.

По результатам анализа сформулированы рекомендации и выводы

Отчет представлен в виде презентации, ссылка https://disk.yandex.ru/i/wA8sqYbh4QeMiQ. 

Ссылка на дашборд https://public.tableau.com/views/__16538420682740/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

