# RegExp
Руководство по регулярным выражениям.

- character
- set
- Повторения

**Регулярное выражение** - это шаблон, который используется для поиска и обработки текста, соответствующего определенным правилам. Они широко используются в программировании и поисковых системах для поиска и фильтрации данных. Они являются мощным инструментом для обработки текста и позволяют создавать гибкие и точные фильтры для определенных типов информации.

Регулярное выражение возвращает совпавший текст или true/false.

## Что такое регулярные выражения
Регулярные выражения связаны с текстом. Регулярные выражения - это инструмент позволяющий эффективно работать с текстом. Благодаря регулярным выражениям можно выяснить что за текст введен, например является ли он емаилом или телефоном. Регулярные выражения крайне важны в программировании и являются тем параметром, которые отделяют просто программиста от хорошего программиста.

Регулярные выражения описывают текстовые паттерны, благодаря которым можно в тексте выделять определённые части.

Регулярное выражен`ие` - это набор символов описывающих текстовой паттерн (RegExp, регулярка).  
регулярные выражен`ия` - формальный язык символов, которые нужно интерпретировать, процессором регулярных выражений.  
Процессор - это то что использует эти символы, чтобы позволить нам находить текст, сопоставлять его и манипулировать им.

Регулярные выражения есть в каждом языке программирования и его синтаксис "паттерны" одинаков, по этому выучив их один раз вы сможете применять регулярные выражения в любом языке.

Регулярные выражения не являются языком программирования, это формальный язык с предопределённым набором правил, которые говорят компьютеру сделать то что мы хотим. Большинство языков программирования используют регулярные выражения.

## Когда используют регулярные выражения
Примеры использования регулярных выражений:
- Проверка количества цифр в телефонном номере,
- Проверка собачки в емаил адресе,
- Поиск в тексте определённых слов,
- Замена в тексте определённых слов,
- Подсчет количества определённых слов в тексте,
- Подсчет количества определённых слов в тексте, при условии что перед ним стоят другие определённые слова,
- Конвертация файла где вместо оступов стоят табы и замена их на запятые,
- Найти повторяющиеся слова в тексте

## Разное
- `matches` - соответствие, регулярное выражение соответствует тексту если корректно описывает этот текст. Текст соответсвует регулярному выражению, если он корректно описывается выражением.
- регулярные выражения не терпеливы

## Ссылки
Онлайн редакторы для проверки регулярных выражений:
- https://www.regexpal.com/
- https://regexr.com/
