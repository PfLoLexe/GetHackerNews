# GetHackerNews
Комплекс python скриптов, реализующий работу с новостным сайтом "news.ycombinator.com"


## Описание содержимого
 - Файл "hackernews.py"
Основной программный файл, реализующий комплексную работу всех подпрограмм, а также обеспечивающий вывод информации и взаимодействие с БД посредством web страниц
 - Файл "scraputils.py"
Подрограмма, реализующая выгрузку новостей с сайта "news.ycombinator.com" для дальнейшей обработки
 - Файл "db.py"
Подрограмма, реализующая работу с базой данных
 - Файл "bayes.py"
Подрограмма, реализующая наивный байесовский классификатор, в т.ч. его обучение на уже классифицированных новостях содержащихся в БД.
