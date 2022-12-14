# Markdown краткий справочник

Markdown (маркда́ун) — язык разметки текста, с максимальным сохранением его читаемости человеком, и пригодный для преобразования в HTML.  


## Курсивный шрифт

Курсивный шрифт создается одноразовым оборачиванием текста с помощью символов * или _:

Это слово выделено *курсивом*. Это слово тоже выделено _курсивом_.  

## Жирный шрифт

Жирный шрифт создается двойным оборачиванием текста с помощью символов * или _:

Это слово выделено как **жирное**. Это слово тоже выделено как __жирное__.

## Маркированный список

Для разметки маркированных списков ul можно использовать или *, -, или + в начале строки:

* Молоко 
* Масло 
* Яблоки

Вложенные пункты создаются пробелами перед маркером пункта:
* Молочные продукты
  * Молоко 
  * Масло 
* Фрукты 
  * Яблоки 
  * Бананы 
  * Апельсины

## Нумерованый список

Для разметки упорядоченных списков ol используются числа:

1. Первый 
2. Второй 
3. Третий

Вложенные пункты создаются пробелами перед маркером пункта:

1. Первый 
2. Второй 
3. Третий 
    1. Первый 
    2. Второй 
    3. Третий

## Ссылки

Ссылки создаются оборачиванием текста в квадратные скобки [] и адреса в круглые ():

Это встроенная [ссылка](http://mychatik.ru/last/).

В круглых скобках, после адреса, в кавычках можно указать значение для аттрибута title:

Это встроенная [ссылка с атрибутом title](http://mychatik.ru/last/ "Последняя страница Интернета")

## Изображение

Изображения создаются с помощью знака ! и квадратных скобок [] между которымы пишется значение для атрибута alt, а также пути к изображению между круглыми скобакми():

![альтернативный текст](800.webp)
Значение для атрибута title можно указать после пути:

![альтернативный текст](https://kartinkin.net/uploads/posts/2021-10/1633788619_29-kartinkin-net-p-sobol-art-krasivo-29.jpg "Куница")

## Абзац

Абзацы создаются при помощи пустой строки:

Другим серьезным направлением на предприятии стало проектирование и производство испытательных стендов для  тестирования арматуры, кабелей, другого оборудования и систем. Существенная часть произведенных стендов предназначалась для НПО «Криогенмаш». Так, продолжая заложенные традиции сегодня, предприятие проектирует и изготавливает испытательный стенд топливных баков для современной ракеты – носителя «Ангара».

В середине 90-х интересный заказ поступил от индийского правительства для космодрома «Шар». Предприятие спроектировало, построило и поставило гелиевые и азотные установки, предназначенные для подготовки топливных баков ракетоносителей под заправку.


## Заголовки

Заголовки отмечаются символом # в начале строки, от одного до шести:

# Заголовок 1 
## Заголовок 2 
### Заголовок 3 
#### Заголовок 4 
##### Заголовок 5 
###### Заголовок 6

## Код

Для выделения части текста в виде кода используется обратная кавычка до и после фрагмента текста:

Для выделения кода в тексте используется элемент `code`.
Для создания блока кода используется три обратные кавычки до и после кода:

``` <h1>Привет мир</h1> ```

После первых трех кавычек можно указать язык блока кода (html, css, js и др.). Это добавит подсветку синтаксиса:

```html <h1>Привет мир</h1> ```

## Цитата

Цитаты blockquote оформляются с помощью символа >:

> Это цитата.

## Горизонтальная линия

Горизонтальная линия hr создается тремя звездочками или тремя дефисами:

--- 
***

