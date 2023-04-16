# Инструкции для работы с MD

## Выделение текста

Чтобы выделить текст курсивовм необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например *вот так* или _вот так_

Чтобы выделить текст полужирным необходимо обрамить его звездочками (**) или двойным знаком нижнего подчеркивания (__). Например **Вот так** или __Вот так__

Альтернативаные способы выделения текста жирным или курсивом нужны для того, чтобы можно было совмещать оба способа. Например, _где-то в этом фрагменте есть еще и **жирный** текст_

Также можно сделать текст зачеркнутым, чтобы это сделать необходимо обрамить фрагмент тильдами (~~). Например, ~~вот так~~

Чтобы оформить горизонтальный разделитель, нужно поставить три или больше специальных символа: звёздочки *, дефиса - или нижних подчёркивания _. Они должны находиться на отдельной строке, и между ними можно ставить любое количество пробелов и табуляций.
Пример:
***
---
___

## Списки

Чтобы выделить ненумерованный список используйте (*)
Чтобы добавить ненумерованные списки, нобходимо пункты выделить звездочкой (*) или знаком +. 

Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, нобходимо пункты пронумеровать.

Например, вот так:
1. Первый пункт
2. Второй пункт 

## Работа с изображениями

Чтобы вставить изображение в текст, надо написать  следующее:
![Упс, не вышло](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA.PNG)

## Ссылки

Чтобы вставить ссылку, можно обрамить ее угольными скобочками (<>)

Например, вот так: <https://skillbox.ru/media/code/yazyk-razmetki-markdown-shpargalka-po-sintaksisu-s-primerami/>

Также можно сделать привязыку ссылки к тексту, чтобы можно было интегрировать ее в текст. Делается это с помощью такой схемы:  [текст](ссылка)

[Ссылка на шпараглку](https://skillbox.ru/media/code/yazyk-razmetki-markdown-shpargalka-po-sintaksisu-s-primerami/)

Еще один способ делать ссылки - сноски. Достаточно указать цифру в квадратных скобках и ниже сделать сноску с такой же цифрой на саму ссылку.
Пример:
[SkillBox][1]

[1]: https://skillbox.ru/media/code/yazyk-razmetki-markdown-shpargalka-po-sintaksisu-s-primerami/


## Работа с таблицами

Чтобы создать таблицу, необходимо разделить текст вертикальными линиями ().Но обязательно после первой строчки надо сделать такую конструкцию |-|, столько раз сколько должно быть столбцов 

Например, вот так:


|1 text|2 Text|3 Text|
|-|-|-|
|12 Text|3 text|dasdas|
|12 Text|3 text|dasdas|
|12 Text|3 text|dasdas|


## Цитати

Чтобы параграф отобразился как цитата, нужно поставить перед ним закрывающую угловую скобку >

> Например вот так

>И еще одна цитата

sdfsdfsdfsdf

## Заключение
git branch - список всех веток.
git branch New_name_branch - добвление новой ветки. 
git branch -d Branch_name - для удаления ненужных веток

git log -graph - красивый вывод изменения файлов в ветках

git merge Branch_name - для слияния ветки с указанной веткой (не забывать переходить в мастер)

git checkout Branch_name - для перехода по разным веткам