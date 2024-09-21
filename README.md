# Сравниваем вакансии программистов
В рамках данного проекта нами была разработана программа, которая автоматически осуществляет поиск вакансий на специализированных сайтах. Основная задача программы заключается в сборе и обработке данных о вакансиях, связанных с различными языками программирования. Программа анализирует количество найденных вакансий, отслеживает, сколько из них было обработано, и на основании собранной информации рассчитывает среднюю зарплату для каждого конкретного языка программирования.

Для получения данных мы интегрировали программу с двумя крупнейшими сайтами по поиску работы: [**HeadHunter**](https://dev.hh.ru/) и [**SuperJob**](https://www.superjob.ru/). Эти платформы предоставляют наиболее полную и актуальную информацию о вакансиях в сфере IT, что позволяет нашему проекту работать с большим количеством данных и получать достоверные результаты.

Программа способна обрабатывать большие объёмы информации, что делает её полезным инструментом для анализа рынка труда, выявления текущих тенденций в зарплатах программистов, а также для оценки востребованности тех или иных языков программирования.

## Установка библиотеки
Для загрузки всех необходимых библиотек впишите в консоль.
```
pip install -r requirements.txt
``` 

## Как запустиь программу
В консоль панели нужно вписать `python api.py`

## Переменные окружения
Создайте файл `.env` рядом с `api.py` и запишите туда данные в формате: ПЕРЕМЕННАЯ=значение.

Пример:
```
SG_TOKEN='SJ_KEY'
```
Получить свой токен (SJ_KEY) вы можете на сайте [API SuperJob](https://api.superjob.ru/).

## Цель проекта
Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
