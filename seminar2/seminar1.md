# Создаём туториал по Git

## Как добавить фаил на отслеживание

Чтобы добавить фаил на отслеживание, используйте следующую команду:
```
git add <название файла.расширение>

```

## Как добавить переключение между коммитами

Чтобы добавить переключение между коммитами, нужно 

ввести следующую команду:

```

git checkout

```

или же:

```
git switch

```
## Как получить информацию о текущем состоянии git

Чтобы получить информацию о текущем состоянии git,

нужно ввести следующую команду:

```
git status

```
## Как увидеть разницу между текущим файлом и закоммиченным файлом

Чтобы увидеть разницу между текущим файлом и закоммиченным файлом, нужно ввести следующую команду:
```
git diff <имена файлов>

```
## Как вывести на экран истории всех коммитов с их хеш-кодами

Чтобы вывести  на экран истории всех коммитов с их хеш-кодами, нужно ввести следующую команду:

```
git log

```
# Краткая инструкция по MarkDown

## Цитаты

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet, > consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.



Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:



> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.


В цитаты можно помещать всё что угодно, в том числе
вложенные цитаты:
> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.


## Заголовки

## Исходный код 

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале
каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ:


 ставим по три апострофа (на букве Ё) до и после кода.

 Также можно указать язык исходного кода.



```HTML
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count" class="publ
isher-nav-color" data-nav="conversation">
 <span class="comment-count">0 комментариев</
span>
 <span class="comment-count-placeholder">Комм
ентарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logou
t">
 <a href="#" class="dropdown-toggle" data-toggl
e="dropdown">
 <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>

```

## Таблицы

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell


Для красоты можно и по бокам линии нарисовать:



| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.



| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |



Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.


Для всего остального есть обычный HTML.
