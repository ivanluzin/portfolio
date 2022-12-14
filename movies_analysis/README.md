# 4. Определение признаков успешных фильмов
## Цель проекта
Изучить рынок российского кинопроката и выявить текущие тренды. Необходимо уделить внимание фильмам, которые получили государственную поддержку и ответить на вопрос, насколько такие фильмы интересны зрителю.
## Данные
Источник данных- портал открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.
## Стек
`pandas` `matplotlib` `Обработка данных` `Анализ данных` `Визуализация данных`
## Что сделано
Предварительная обработка данных, заполнение пропусков, удаление дубликатов, унификация страны-производителя фильма, унификация жанров, выполнена категоризация данных по государственной поддержке, выполнен исследовательский анализ данных.
## Выводы
* В интервале с 2010 по 2019 год наибольшее количество фильмов вышло в 2010 году. Возможно, это связано с экономическим кризисом 2008 года и приостановкой работы над фильмами. Наименьшее количество фильмов вышло в 2017 году, однако в этом же году фильмы являются наиболее кассовыми по сравнению с остальными. Это объясняется тем, что в 2017 году резко выросло производство художественных и анимационных фильмов.
* Более кассовыми являются художественные и анимационные фильмы с мягкими возрастными ограничениями. Больше всего денег собирают фильмы категорий "0+" и "6+". На эти фильмы чаще всего дети идут в сопровождении родителей, что увеличивает количество билетов, продаваемых в кино. Наименьшие сборы- у фильмов "18+". На общие сборы влияет и сезон выхода фильма- фильм, вышедший зимой в среднем соберет кассу больше, чем фильм, вышедший летом. Рейтинг фильма не оказывает особого влияния на его кассовые сборы.
* При получении государственной поддержки производители фильма стараются получить максимальный ее объем- 70% от общего бюджета фильма. Большая часть из этих денег является невозвратной. Окупаются в прокате 33% фильмов, получивших поддержку. В целом, наблюдается тенденция роста государственной поддержки российских фильмов. Чаще всего фильмы, получившие поддержку- это драмы и комедии, выходящие с возрастными ограничениями "12+" и "16+".
