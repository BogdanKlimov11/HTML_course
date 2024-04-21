 <h1 id="top">Справочник по языку разметки HTML</h1>

<img src="https://github.com/BogdanKlimov11/HTML_course/assets/136115919/3e9a9a83-7cd0-43c8-a930-f7e873bf628f" alt="HTML logo" title="HTML" width="100%" height="auto">

---

<!-- Оглавление -->
<h2>Оглавление</h2>
<nav>
    <ol>
        <li><a href="#раздел-1">Введение</a></li>
        <li><a href="#раздел-2">Теги по категориям</a></li>
        <ul>
            <li><a href="#подраздел-2.1">Теги основные</a></li>
            <li><a href="#подраздел-2.2">Теги форматирования</a></li>
            <li><a href="#подраздел-2.3">Теги форм ввода</a></li>
            <li><a href="#подраздел-2.4">Теги фреймов</a></li>
            <li><a href="#подраздел-2.5">Теги изображений</a></li>
            <li><a href="#подраздел-2.6">Теги Аудио/Видео</a></li>
            <li><a href="#подраздел-2.7">Теги ссылок</a></li>
            <li><a href="#подраздел-2.8">Теги списка</a></li>
            <li><a href="#подраздел-2.9">Теги таблицы</a></li>
            <li><a href="#подраздел-2.10">Теги стиля и семантики</a></li>
            <li><a href="#подраздел-2.11">Теги мета информации</a></li>
            <li><a href="#подраздел-2.12">Теги программирования</a></li>
            <li><a href="#подраздел-2.13">Полный список тегов</a></li>
            <li><a href="#подраздел-2.14">Полный список атрибутов</a></li>
        </ul>
        <li><a href="#раздел-3">Методы запроса HTTP</a></li>
        <li><a href="#раздел-4">Сообщения ошибок</a></li>
        <ul>
            <li><a href="#подраздел-4.1">1xx: Информация</a></li>
            <li><a href="#подраздел-4.2">2xx: Успешный</a></li>
            <li><a href="#подраздел-4.3">3xx: Переадресация</a></li>
            <li><a href="#подраздел-4.4">4xx: Ошибка клиента</a></li>
            <li><a href="#подраздел-4.5">5xx: ошибка сервера</a></li>
        </ul>
    </ol>
</nav>

---

<!-- Разделы -->
<h2 id="раздел-1">Введение <a href="#top">↑top↑</a></h2>

**HTML (HyperText Markup Language — «язык гипертекстовой разметки»)** — стандартизированный язык 
гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают 
HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее 
интерпретируют код в интерфейс, который будет отображаться на экране монитора.

Элементы HTML являются строительными блоками HTML страниц. С помощью HTML разные конструкции, 
изображения и другие объекты, такие как интерактивная веб-форма, могут быть встроены в отображаемую 
страницу. HTML предоставляет средства для создания заголовков, абзацев, списков, ссылок, цитат и 
других элементов. Элементы HTML выделяются тегами, записанными с использованием угловых скобок. 
Такие теги, как `<img />` и `<input />`, напрямую вводят контент на страницу. Другие теги, такие 
как `<p>`, окружают и оформляют текст внутри себя и могут включать другие теги в качестве 
подэлементов. Браузеры не отображают HTML-теги, но используют их для интерпретации содержимого 
страницы.

Язык **XHTML** является более строгим вариантом HTML, он следует синтаксису XML и является 
приложением языка XML в области разметки гипертекста.

* В HTML можно встроить язык программирования **JavaScript** с помощью тега.

* Также включение **CSS** в HTML позволяет задавать внешний вид и макет страницы.

Пример базового кода HTML можно посмотреть <a href="https://github.com/BogdanKlimov11/HTML_course/blob/main/Resources/Example.html">здесь</a>.

---

<!-- Теги по алфавиту -->
<h2 id="раздел-2">Теги по категориям <a href="#top">↑top↑</a></h2>

Здесь расположены все теги по категориям и лишь из краткое описание. Полный список с подробным 
описанием и расположенным в алфавитном порядке можно найти в разделе <a href="#подраздел-2.13">"Полный список тегов"</a>

<h3 id="подраздел-2.1">Теги основные <a href="#top">↑top↑</a></h3>

`<!DOCTYPE>` - определяет тип документа

`<html>` - определяет документ в HTML

`<head>` - определяет информацию о документе

`<title>` - определяет название для документа

`<body>` - определяет тело документа

`<h1>` до `<h6>` - определяет заголовки

`<p>` - определяет параграф

`<br>` - вставляет разрыв строки

`<hr>` - определяет тематическое изменение в содержании

`<!--...-->` - определяет комментарий

<h3 id="подраздел-2.2">Теги форматирования <a href="#top">↑top↑</a></h3>

`<acronym>` - определяет акроним (не поддерживается в HTML5; лучше используйте `<abbr>`)

`<abbr>` - определяет аббревиатуру или акроним

`<address>` - определяет контактную информацию для автора/владельца из документа/статьи

`<b>` - определяет полужирный текст

`<bdi>` - изолирует часть текста, которая может быть отформатирована в другом направлении, от 
другого текста за его пределами

`<bdo>` - переопределяет текущее направление текста

`<big>` - определяет большой текст (не поддерживается в HTML5; лучше используйте CSS)

`<blockquote>` - определяет раздел, заключенный в кавычки из другого источника

`<center>`- определяет центрированный текст (не поддерживается в HTML5; лучше используйте CSS)

`<cite>` - определяет название из работы

`<code>` - определяет часть из компьютерного кода

`<del>` - определяет текст, который был удален из документа

`<dfn>` - представляет определяющий экземпляр термина

`<em>` - определяет подчеркнутый текст

`<font>` - определяет шрифт, цвет и размер текста (не поддерживается в HTML5; лучше используйте 
CSS)

`<i>` - определяет часть текста альтернативным голосом или настроением

`<ins>` - определяет текст, вставленный в документ

`<kbd>` - определяет ввод с клавиатуры

`<mark>` - определяет выделенный / выделенный текст

`<meter>` - определяет скалярное измерение в известном диапазоне (датчик)

`<pre>` - определяет форматированный текст

`<progress>` - представляет ход выполнения задачи

`<q>` - определяет короткую цитату

`<rp>` - определяет, что показывать в браузерах, которые не поддерживают аннотации ruby

`<rt>` - определяет объяснение/произношение символов (для Восточно-Азиатской типографии)

 `<ruby>` - определяет аннотацию ruby (для Восточно-Азиатской типографии)

`<s>` - определяет текст, который больше не является правильным

`<samp>` - определяет пример вывода из компьютерной программы

`<small>` - определяет меньший текст

`<strike>` - определяет зачеркнутый текст (не поддерживается в HTML5; лучше используйте `<del>` 
или `<s>`)

`<strong>` - определяет строгий текст

`<sub>` - определяет подстрочный текст

`<sup>` - определяет надстрочный текст

`<template>` - определяет шаблон

`<time>` - определяет дату/время

`<tt>` - определяет текст телетайпа (не поддерживается в HTML5; лучше используйте CSS)

`<u>` - определяет текст, который должен стилистически отличаться от обычного текста

`<var>` - определяет переменную

`<wbr>` - определяет возможный разрыв строки

<h3 id="подраздел-2.3">Теги форм ввода <a href="#top">↑top↑</a></h3>

`<form>` - определяет форму HTML для пользовательского ввода

`<input>` - определяет ввод управления

`<textarea>` - определяет многострочный ввод (текстовое поле)

`<button>`- определяет кликабельную кнопку

`<select>` - определяет раскрывающийся список

`<optgroup>` - определяет группу связанных параметров в раскрывающемся списке

`<option>` - определяет параметр в раскрывающемся списке

`<label>` - определяет метку для элемента <input>

`<fieldset>` - группирует связанные элементы в форме

`<legend>` - определяет заголовок для элемента <fieldset>

`<datalist>` - задает список предопределенных параметров для элементов управления вводом

`<output>` - определяет результат вычисления

<h3 id="подраздел-2.4">Теги фреймов <a href="#top">↑top↑</a></h3>

`<frame>` - определяет окно (фрейм) в наборе кадров (не поддерживается в HTML5)

`<frameset>` - определяет набор фреймов (не поддерживается в HTML5)

`<noframes>` - определяет альтернативное содержимое для пользователей, не поддерживающих фреймы 
(не поддерживается в HTML5)

`<iframe>` - определяет встроенный фрейм

<h3 id="подраздел-2.5">Теги изображений <a href="#top">↑top↑</a></h3>

`<img>` - определяет изображение

`<map>` - определяет клиентскую карту изображений

`<area>` - определяет область внутри изображения карты

`<canvas>` - используется для рисования графики по ходу, с помощью скриптов (обычно код 
JavaScript)

`<figcaption>` - определяет заголовок для элемента `<figure>`

`<figure>` - задает автономное содержимое

`<picture>` - определяет контейнер для нескольких ресурсов изображений

`<svg>` - определяет контейнер для графики SVG

<h3 id="подраздел-2.6">Теги Аудио/Видео <a href="#top">↑top↑</a></h3>

`<audio>` - определяет звук контента

`<source>` - определяет несколько ресурсов мультимедиа для элементов медиа (`<video>`, 
`<audio>` и `<picture>`)

`<track>` - определяет текстовые дорожки для элементов медиа (`<video>` и `<audio>`)

`<video>` - определяет видео или фильм

<h3 id="подраздел-2.7">Теги ссылок <a href="#top">↑top↑</a></h3>

`<a>` - определяет гиперссылку

`<link>` - определяет связь между документом и внешним ресурсом (наиболее часто используемым для 
связи с таблицами стилей)

`<nav>` - определяет навигацию ссылок

<h3 id="подраздел-2.8">Теги списка <a href="#top">↑top↑</a></h3>

`<ul>` - определяет неупорядоченный список

`<ol>` - определяет упорядоченный список

`<li>` - определяет элемент списка

`<dir>` - определяет каталог списка (не поддерживается в HTML5; лучше используйте `<ul>`)

`<dl>` - определяет описание списка

`<dt>` - определяет термин/имя в списке описания

`<dd>` - определяет описание термина/имени в списке описания

`<menu>` - определяет список/меню команд

`<menuitem>` - определяет команду/меню, которые пользователь может вызвать из всплывающего 
меню

<h3 id="подраздел-2.9">Теги таблицы <a href="#top">↑top↑</a></h3>

`<table>` - определяет таблицу

`<caption>` - определяет заголовок в таблицы

`<th>` - определяет заголовк ячейки в таблице

`<tr>` - определяет строку в таблице

`<td>` - определяет ячейку в таблице

`<thead>` - группирует содержимое заголовка в таблице

`<tbody>` - группирует содержимое тела в таблице

`<tfoot>` - группирует содержание нижнего колонтитула в таблице

`<col>` - задает свойства столбца для каждого столбца в элементе `<colgroup>`

`<colgroup>` - задает группу из одного или нескольких столбцов в таблице для форматирования

<h3 id="подраздел-2.10">Теги стиля и семантики <a href="#top">↑top↑</a></h3>

`<style>` - определяет информацию о стиле документа

`<div>` - определяет контейнер в документе

`<span>` - определяет промежуток в документе

`<header>` - определяет заголовок документа или раздела

`<footer>` - определяет нижний колонтитул для документа или раздела

`<main>` - определяет основное содержание документа

`<section>` - определяет раздел в документе

`<article>` - определение статьи

`<aside>` - определяет содержимое из содержимого страницы

`<details>` - определяет дополнительные сведения, которые пользователь может просмотреть или скрыть

`<dialog>` - определяет диалоговое окно или окно

`<summary>` - определяет видимый заголовок элемента `<details>`

`<data>` - связывает данный контент с машиночитаемым переводом

<h3 id="подраздел-2.11">Теги мета информации <a href="#top">↑top↑</a></h3>

`<head>` - Определяет информацию о документе

`<meta>` - Определяет метаданные о документе HTML

`<base>` - Задает базовый URL/цель для всех относительных URL адресов в документе

`<basefont>` - задает цвет, размер и шрифт по умолчанию для всего текста в документе (не поддерживается 
в HTML5; лучше используйте CSS)

<h3 id="подраздел-2.12">Теги программирования <a href="#top">↑top↑</a></h3>

`<script>` - определяет клиентский сценарий

`<noscript>` - определяет альтернативное содержимое для пользователей, не поддерживающих клиентские 
сценарии

`<applet>` - определяет встроенный апплет (не поддерживается в HTML5; лучше используйте `<embed>` или 
`<object>`)

`<embed>` - определяет контейнер для внешнего (не-HTML) приложения

`<object>` - определяет внедренный объект

`<param>` - определяет параметр для объекта

<h3 id="подраздел-2.13">Полный список тегов <a href="#top">↑top↑</a></h3>

<!-- Оглавление -->
<h3>Оглавление</h3>
<nav>
    <ol>
        <li><a href="#!">!</a></li>
        <li><a href="#A">A</a></li>
        <li><a href="#B">B</a></li>
        <li><a href="#C">C</a></li>
        <li><a href="#D">D</a></li>
        <li><a href="#E">E</a></li>
        <li><a href="#F">F</a></li>
        <li><a href="#H">H</a></li>
        <li><a href="#I">I</a></li>
        <li><a href="#K">K</a></li>
        <li><a href="#L">L</a></li>
        <li><a href="#M">M</a></li>
        <li><a href="#N">N</a></li>
        <li><a href="#O">O</a></li>
        <li><a href="#P">P</a></li>
        <li><a href="#Q">Q</a></li>
        <li><a href="#R">R</a></li>
        <li><a href="#S">S</a></li>
        <li><a href="#T">T</a></li>
        <li><a href="#U">U</a></li>
        <li><a href="#V">V</a></li>
        <li><a href="#W">W</a></li>
        <li><a href="#X">X</a></li>
    </ol>
</nav>

---

<!-- Разделы -->
<h3 id="!">! <a href="#top">↑top↑</a></h3>

`<!DOCTYPE>`

**Описание**

Элемент `<!DOCTYPE>` предназначен для указания типа текущего документа 
— DTD (document type definition, описание типа документа). Это необходимо, 
чтобы браузер понимал, как следует интерпретировать текущую веб-страницу, 
поскольку HTML существует в нескольких версиях, кроме того, имеется XHTML 
(EXtensible HyperText Markup Language, расширенный язык разметки 
гипертекста), похожий на HTML, но различающийся с ним по синтаксису. 
Чтобы браузер «не путался» и понимал, согласно какому стандарту отображать 
веб-страницу и необходимо в первой строке кода задавать `<!DOCTYPE>`.

Существует несколько видов `<!DOCTYPE>`, они различаются в зависимости от 
версии языка, на которого ориентированы. Здесь приведены основные типы 
документов с их описанием.

**HTML 4.01**

<table>
    <tr>
        <th>DOCTYPE</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd"&#62;</code>
        </td>
        <td>Строгий синтаксис HTML.</td>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd"&#62;</code>
        </td>
        <td>Переходный синтаксис HTML.</td>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd"&#62;</code>
        </td>
        <td>В HTML-документе применяются фреймы.</td>
    </tr>
</table>

**HTML 5**

<table>
    <tr>
        <th>DOCTYPE</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE html&#62;</code>
        </td>
        <td>Для всех документов.</td>
    </tr>
</table>

**XHTML 1.0**

<table>
    <tr>
        <th>DOCTYPE</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"&#62;</code>
        </td>
        <td>Строгий синтаксис XHTML.</td>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"&#62;</code>
        </td>
        <td>Переходный синтаксис XHTML.</td>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd"&#62;</code>
        </td>
        <td>Документ написан на XHTML и содержит фреймы.</td>
    </tr>
</table>

**XHTML 1.1**

<table>
    <tr>
        <th>DOCTYPE</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>
            <code>&#60;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd"&#62;</code>
        </td>
        <td>
            Разработчики XHTML 1.1 предполагают, что он постепенно вытеснит 
            HTML. Никакого деления на виды это определение не имеет, синтаксис 
            один и подчиняется четким правилам.
        </td>
    </tr>
</table>

**Синтаксис**

```html
<!DOCTYPE [Элемент верхнего уровня] [Публичность] "[Регистрация]//[Организация]//[Тип] [Имя]//[Язык]" "[URL]">
```

**Атрибуты**

Нет.

---

`<!-- -->`

**Описание**

Тег добавляет комментарий в код документа. Текст комментария не отображается 
на странице. Разрешается внутрь комментария добавлять другие теги, вложенные 
комментарии (когда один комментарий расположен внутри другого) недопустимы.

**Синтаксис**

```html
<!-- текст -->
```

**Атрибуты**

Нет.

---

<h3 id="A">A <a href="#top">↑top↑</a></h3>

`<a>`

**Описание**

Тег `<a>` является одним из важных элементов HTML и предназначен для создания 
ссылок. В зависимости от присутствия атрибутов `name` или `href` тег `<a>` 
устанавливает ссылку или якорь. Якорем называется закладка внутри страницы, 
которую можно указать в качестве цели ссылки. При использовании ссылки, которая 
указывает на якорь, происходит переход к закладке внутри веб-страницы.

Для создания ссылки необходимо сообщить браузеру, что является ссылкой, а также 
указать адрес документа, на который следует сделать ссылку. В качестве значения 
атрибута `href` используется адрес документа (URL, Universal Resource Locator, 
универсальный указатель ресурсов), на который происходит переход. Адрес ссылки 
может быть абсолютным и относительным. Абсолютные адреса работают везде и всюду 
независимо от имени сайта или веб-страницы, где прописана ссылка. Относительные 
ссылки, как следует из их названия, построены относительно текущего документа 
или корня сайта.

**Синтаксис**

```html
<a href="URL">...</a>
<a name="идентификатор">...</a>
```

**Атрибуты**

* `accesskey` - активация ссылки с помощью комбинации клавиш.

* `coords` - устанавливает координаты активной области.

* `download` - предлагает скачать указанный по ссылке файл.

* `href` - задает адрес документа, на который следует перейти.

* `hreflang` - идентифицирует язык текста по ссылке.

* `name` - устанавливает имя якоря внутри документа.

* `rel` - отношения между ссылаемым и текущим документами.

* `rev` - отношения между текущим и ссылаемым документами.

* `shape` - задает форму активной области ссылки для изображений.

* `tabindex` - определяет последовательность перехода между ссылками при нажатии
  на кнопку <kbd>Tab</kbd>.

* `target` - имя окна или фрейма, куда браузер будет загружать документ.

* `title` - добавляет всплывающую подсказку к тексту ссылки.

* `type` - указывает MIME-тип документа, на который ведёт ссылка.

Также для этого тега доступны универсальные атрибуты и события.

---

`<abbr>`

**Описание**

Тег `<abbr>` указывает, что последовательность символов является аббревиатурой. 
С помощью атрибута `title` дается расшифровка сокращения, что позволяет понимать 
аббревиатуру тем людям, которые с ней не знакомы. Кроме того, поисковые системы 
индексируют полнотекстовый вариант сокращения, что может использоваться для 
повышения рейтинга документа.

Браузеры никак не выделяют текст внутри `<abbr>`, за исключением Opera до версии 
15, которая добавляет к тексту пунктирное подчёркивание.

**Синтаксис**

```html
<abbr>Текст</abbr>
```

**Атрибуты**

* `title` - добавляет всплывающую подсказку к тексту, в которой можно дать расшифровку
  аббревиатуры.

Также для этого тега доступны глобальные атрибуты и события.

---

`<acronym>`

**Описание**

Тег `<acronym>` указывает на то, что текст является акронимом. В отличие от аббревиатуры, 
акроним — это устоявшееся сокращение, которое применяется как самостоятельное слово. К 
акронимам, например, можно отнести следующие слова: СПИД, ликбез, замполит, США, DOS и 
др.

По умолчанию, текст заключенный в контейнере `<acronym>` подчеркивается пунктирной 
линией.

**Синтаксис**

```html
<acronym>Текст</acronym>
```

**Атрибуты**

Для этого тега доступны универсальные атрибуты и события.

---

`<address>`

**Описание**

Тег `<address>` предназначен для хранения информации об авторе и может включать в себя 
любые элементы HTML вроде ссылок, текста, выделений и т.д. Планируется, что поисковые 
системы будут анализировать содержимое этого тега для сбора информации об авторах сайтов.

По умолчанию текст внутри контейнера <address> отображается курсивным начертанием. Если 
эта особенность не требуется, используйте стили для изменения начертания шрифта.

**Синтаксис**

```html
<address>Текст</address>
```

**Атрибуты**

Для этого тега доступны универсальные атрибуты и события.

---

`<applet>`

**Описание**

Тег `<applet>` предназначен для вставки на страницу апплетов — небольших программ, 
написанных на языке Java. Этот тег является устаревшим, взамен необходимо использовать 
более гибкий тег `<object>`. Между открывающим и закрывающим тегом можно добавить текст, 
который будет отображаться в браузере, если он не поддерживает апплеты. В противном 
случае текст не выводится.

**Синтаксис**

```html
<applet code="URL">Текст</applet>
```

**Атрибуты**

* `align` - задает выравнивание апплета относительно близлежащих элементов и текста.

* `alt` - альтернативный текст.

* `archive` - указывает путь и имя файла с архивом.

* `code` - имя файла.

* `codebase` - путь к папке с апплетом, который задан атрибутом `code`.

* `height` - высота апплета.

* `hspace` - горизонтальный отступ от апплета до окружающего контента.

* `vspace` - вертикальный отступ от апплета до окружающего контента.

* `width` - ширина апплета.

Также для этого тега доступны универсальные атрибуты и события.

---

`<area>`

**Описание**

Каждый элемент `<area>` определяет активные области изображения, которые являются 
ссылками. Рисунок с привязанными к нему активными областями называется в совокупности 
картой-изображением. Такая карта по внешнему виду ничем не отличается от обычного 
изображения, но при этом оно может быть разбито на невидимые зоны разной формы, где 
каждая из областей служит ссылкой. Тег `<area>` задает форму области, ее размеры, 
устанавливает адрес документа, на который следует сделать ссылку, а также имя окна 
или фрейма, куда браузер будет загружать документ. Этот тег всегда располагается в 
контейнере `<map>`, который связывает координаты областей с изображением.

Несколько областей могут перекрывать друг друга, сверху будет та, которая в коде 
HTML располагается выше.

**Синтаксис**

**HTML**

 ```html
<map>
  <area href="URL">
</map>
```

**XHTML**

```html
<map>
  <area href="URL" />
</map>
```

**Атрибуты**

* `accesskey` - переход к области с помощью комбинации клавиш.

* `alt` - альтернативный текст для области изображения.

* `coords` - координаты активной области.

* `href` - задает адрес документа, на который следует перейти.

* `hreflang` - указывает язык документа, на который ведет ссылка.

* `nohref` - область без ссылки на другой документ.

* `shape` - форма области.

* `tabindex` - задает последовательность перехода между элементами с помощью клавиши
  <kbd>Tab</kbd>.

* `target` - имя окна или фрейма, куда браузер будет загружать документ.

* `type` - устанавливает MIME-тип документа, на который ведёт ссылка.

Также для этого тега доступны универсальные атрибуты и события.

---

`<article>`

**Описание**

Тег `<article>` задает содержание сайта вроде новости, статьи, записи блога, форума 
или др.

**Синтаксис**

```html
<article>
</article>
```

**Атрибуты**

Нет.

---

`<aside>`

**Описание**

Определяет блок сбоку от контента для размещения рубрик, ссылок на архив, меток и 
другой информации. Такой блок, как правило, называется «сайдбар» или «боковая 
панель».

**Синтаксис**

```html
<aside>
</aside>
```

**Атрибуты**

Для этого тега доступны универсальные атрибуты.

---

`<audio>`

**Описание**

Добавляет, воспроизводит и управляет настройками аудиозаписи на веб-странице. Путь 
к файлу задается через атрибут `src` или вложенный тег `<source>`. Внутри контейнера 
`<audio>` можно написать текст, который будет выводиться в браузерах, не работающих 
с этим тегом.

**Синтаксис**

```html
<audio src="URL"></audio>
<audio>
 <source src="URL">
</audio>
```

**Атрибуты**

* `autoplay` - звук начинает играть сразу после загрузки страницы.

* `controls` - добавляет панель управления к аудиофайлу.

* `loop` - повторяет воспроизведение звука с начала после его завершения.

* `preload` - используется для загрузки файла вместе с загрузкой веб-страницы.

* `src` - указывает путь к воспроизводимому файлу.

---

<h3 id="B">B <a href="#top">↑top↑</a></h3>

---

<h3 id="C">C <a href="#top">↑top↑</a></h3>

---

<h3 id="D">D <a href="#top">↑top↑</a></h3>

---

<h3 id="E">E <a href="#top">↑top↑</a></h3>

---

<h3 id="F">F <a href="#top">↑top↑</a></h3>

---

<h3 id="H">H <a href="#top">↑top↑</a></h3>

---

<h3 id="I">I <a href="#top">↑top↑</a></h3>

---

<h3 id="K">K <a href="#top">↑top↑</a></h3>

---

<h3 id="L">L <a href="#top">↑top↑</a></h3>

---

<h3 id="M">M <a href="#top">↑top↑</a></h3>

---

<h3 id="N">N <a href="#top">↑top↑</a></h3>

---

<h3 id="O">O <a href="#top">↑top↑</a></h3>

---

<h3 id="P">P <a href="#top">↑top↑</a></h3>

---

<h3 id="Q">Q <a href="#top">↑top↑</a></h3>

---

<h3 id="R">R <a href="#top">↑top↑</a></h3>

---

<h3 id="S">S <a href="#top">↑top↑</a></h3>

---

<h3 id="T">T <a href="#top">↑top↑</a></h3>

---

<h3 id="U">U <a href="#top">↑top↑</a></h3>

`<u>`

**Описание**

Добавляет подчеркивание к тексту. Этот тег осуждается спецификацией HTML, взамен 
рекомендуется использовать стили.

**Синтаксис**

```html
<u>Текст</u>
```

**Атрибуты**

Нет.

**Аналог CSS**

`text-decoration`

---

`<ul>`

**Описание**

Тег `<ul>` устанавливает маркированный список. Каждый элемент списка должен 
начинаться с тега `<li>`. Если к тегу `<ul>` применяется таблица стилей, то 
элементы `<li>` наследуют эти свойства.

**Синтаксис**

```html
<ul>
  <li>элемент маркированного списка</li>
</ul>
```

**Атрибуты**

* `type` - устанавливает вид маркера списка.

Также для этого тега доступны универсальные атрибуты и события.

---

<h3 id="V">V <a href="#top">↑top↑</a></h3>

`<var>`

**Описание**

Тег `<var>` используется для выделения переменных компьютерных программ. Браузеры 
обычно помечают текст в контейнере <var> курсивным начертанием.

**Синтаксис**

```html
<var>Текст</var>
```

**Атрибуты**

Для этого тега доступны универсальные атрибуты и события.

---

`<video>`

**Описание**

Добавляет, воспроизводит и управляет настройками видеоролика на веб-странице. Путь 
к файлу задается через атрибут `src` или вложенный тег `<source>`.

**Синтаксис**

```html
<video>
 <source src="URL">
</video>
```

**Атрибуты**

* `autoplay` - Видео начинает воспроизводиться автоматически после загрузки страницы.

* `controls` - Добавляет панель управления к видеоролику.

* `height` - Задает высоту области для воспроизведения видеоролика.

* `loop` - Повторяет воспроизведение видео с начала после его завершения.

* `poster` - Указывает адрес картинки, которая будет отображаться, пока видео не
  доступно или не воспроизводится.

* `preload` - Используется для загрузки видео вместе с загрузкой веб-страницы.

* `src` - Указывает путь к воспроизводимому видеоролику.

* `width` - Задает ширину области для воспроизведения видеоролика.

---

<h3 id="W">W <a href="#top">↑top↑</a></h3>

`<wbr>`

**Описание**

Тег `<wbr>` указывает браузеру место, где допускается делать перенос строки в 
тексте, если этого требует ширина родительского элемента.

**Синтаксис**

```html
Текст<wbr>текст
```

**Атрибуты**

Нет.

---

<h2 id="X">X <a href="#top">↑top↑</a></h2>

`<xmp>`

**Описание**

Тег `<xmp>` отображает содержимое контейнера «как есть» и шрифтом фиксированной 
ширины. Пока тег `<xmp>` не закрыт, все теги внутри него отображаются как обычный 
текст.

**Синтаксис**

```html
<xmp>Текст</xmp>
```

**Атрибуты**

Нет.

<h3 id="подраздел-2.14">Полный список атрибутов <a href="#top">↑top↑</a></h3>

<table>
    <tr>
        <th>Имя атрибута</th>
        <th>Элементы</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td><code>hidden</code></td>
        <td>Глобальный атрибут</td>
        <td>Предотвращает генерирование данного элемента, в то время как сохраняет дочерние элементы, например, элементы script, active.</td>
    </tr>
    <tr>
        <td><code>something</code></td>
        <td>something</td>
        <td>something</td>
    </tr>
</table>

---

<h2 id="раздел-3">Методы запроса HTTP <a href="#top">↑top↑</a></h2>

<table>
    <tr>
        <th>Метод</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>GET</td>
        <td>Запрашивает данные из указанного ресурса</td>
    </tr>
    <tr>
        <td>POST</td>
        <td>Отправляет данные для обработки указанному ресурсу</td>
    </tr>
    <tr>
        <td>HEAD</td>
        <td>То же, что и GET, но возвращает только заголовки HTTP, а не тело документа</td>
    </tr>
    <tr>
        <td>PUT</td>
        <td>Загружает представление указанного URI</td>
    </tr>
    <tr>
        <td>DELETE</td>
        <td>Удаляет указанный ресурс</td>
    </tr>
    <tr>
        <td>OPTIONS</td>
        <td>Возвращает методы HTTP, поддерживаемые сервером</td>
    </tr>
    <tr>
        <td>CONNECT</td>
        <td>Преобразует соединение запроса в прозрачный туннель TCP/IP</td>
    </tr>
</table>

---

<h2 id="раздел-4">Сообщения ошибок <a href="#top">↑top↑</a></h2>

Когда браузер запрашивает службу с веб сервера, может возникнуть ошибка. Это список сообщений 
о состоянии HTTP, которые могут быть возвращены.

<h3 id="подраздел-4.1">1xx: Информация <a href="#top">↑top↑</a></h3>

<table>
    <tr>
        <th>Сообщение</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>100 Продолжать</td>
        <td>Сервер получил заголовки запроса и клиент должен продолжить отправлять тело запроса</td>
    </tr>
    <tr>
        <td>101 Протоколы коммутации</td>
        <td>some</td>
    </tr>
    <tr>
        <td>103 Контрольная точка</td>
        <td>Используется в предложении для возобновления прерванных запросов PUT или POST</td>
    </tr>
</table>

<h3 id="подраздел-4.2">2xx: Успешный <a href="#top">↑top↑</a></h3>

<table>
    <tr>
        <th>Сообщение</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>200 Хорошо</td>
        <td>Запрос в порядке (это стандартный ответ для успешных запросов HTTP)</td>
    </tr>
    <tr>
        <td>201 Создан</td>
        <td>Запрос выполнен, создан новый ресурс</td>
    </tr>
    <tr>
        <td>202 Признанный</td>
        <td>Запрос принят к обработке, но обработка не завершена</td>
    </tr>
    <tr>
        <td>203 Не Достоверная информация</td>
        <td>Запрос успешно обработан, но возвращает информацию, которая может быть из другого источника</td>
    </tr>
    <tr>
        <td>204 Нет содержания</td>
        <td>Запрос успешно обработан, но не возвращает никакого содержимого</td>
    </tr>
    <tr>
        <td>205 Сброс содержимого</td>
        <td>Запрос успешно обработан, но не возвращает никакого содержимого и требует, чтобы инициатор запроса сбросил представление документа</td>
    </tr>
    <tr>
        <td>206 Частичное содержимое</td>
        <td>Сервер доставляет только часть ресурса из-за заголовка диапазона, отправленного клиентом</td>
    </tr>
</table>

<h3 id="подраздел-4.3">3xx: Переадресация <a href="#top">↑top↑</a></h3>

<table>
    <tr>
        <th>Сообщение</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>300 Множественный выбор</td>
        <td>Cписок ссылок. Пользователь может выбрать ссылку и перейти в это место. Максимум пять адресов</td>
    </tr>
    <tr>
        <td>301 Перемещено постоянно</td>
        <td>Запрашиваемая страница перемещена на новый адрес</td>
    </tr>
    <tr>
        <td>302 Найдено</td>
        <td>Запрошенная страница временно перемещена на новый URL</td>
    </tr>
    <tr>
        <td>303 Видеть других</td>
        <td>Запрашиваемую страницу можно найти по другому URL</td>
    </tr>
    <tr>
        <td>304 Не модифицировать</td>
        <td>Указывает, что запрашиваемая страница не была изменена с момента последнего запроса</td>
    </tr>
    <tr>
        <td>306 Переключить прокси</td>
        <td>Больше не использовать</td>
    </tr>
    <tr>
        <td>307 Временное перенаправление</td>
        <td>Запрошенная страница временно перемещена на новый URL</td>
    </tr>
    <tr>
        <td>308 Резюме неполное</td>
        <td>Используется в предложении для возобновления прерванных запросов PUT или POST</td>
    </tr>
</table>

<h3 id="подраздел-4.4">4xx: Ошибка клиента <a href="#top">↑top↑</a></h3>

<table>
    <tr>
        <th>Сообщение</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>400 Плохой запрос</td>
        <td>Запрос не может быть выполнен из-за плохого синтаксиса</td>
    </tr>
    <tr>
        <td>401 Несанкционированный</td>
        <td>Запрос был законным, но сервер отказывается отвечать на него. Для использования при аутентификации можно, но не еще не обеспечено</td>
    </tr>
    <tr>
        <td>402 Требуется оплата</td>
        <td>Зарезервировано для использования в будущем</td>
    </tr>
    <tr>
        <td>403 Под запретом</td>
        <td>Запрос был законным, но сервер отказывается отвечать на него</td>
    </tr>
    <tr>
        <td>404 не найдено</td>
        <td>Запрашиваемая страница не может быть найдена, но может быть доступна в будущем</td>
    </tr>
    <tr>
        <td>405 Метод не допускается</td>
        <td>Запрос страницы был сделан с использованием метода запроса, не поддерживаемого этой страницей</td>
    </tr>
    <tr>
        <td>406 Не приемлемый</td>
        <td>Сервер может только генерировать ответ, который не принимается клиентом</td>
    </tr>
    <tr>
        <td>407 Требуется проверка подлинности прокси</td>
        <td>Клиент должен сначала аутентифицироваться с прокси</td>
    </tr>
    <tr>
        <td>408 Время ожидания запроса</td>
        <td>Время ожидания запроса истекло</td>
    </tr>
    <tr>
        <td>409 Конфликт</td>
        <td>Запрос не удалось выполнить из-за конфликта в запросе</td>
    </tr>
    <tr>
        <td>410 Пропащий</td>
        <td>Запрашиваемая страница больше не доступна</td>
    </tr>
    <tr>
        <td>411 Требуемая длина</td>
        <td>"Длина содержимого" не определена. Сервер не примет запрос без него</td>
    </tr>
    <tr>
        <td>412 Не удалось выполнить предварительное условие</td>
        <td>Предварительное условие, указанное в запросе, оцененном сервером как false</td>
    </tr>
    <tr>
        <td>413 Слишком большой объект запроса</td>
        <td>Сервер не примет запрос, так как объект запроса слишком велик</td>
    </tr>
    <tr>
        <td>414 Запрос URL слишком длинный</td>
        <td>Сервер не примет запрос, так как URL слишком длинный. Имеет место при преобразовании запроса POST в запрос GET с длинными сведениями о запросе</td>
    </tr>
    <tr>
        <td>415 Неподдерживаемый тип носителя</td>
        <td>Сервер не примет запрос, так как тип носителя не поддерживается</td>
    </tr>
    <tr>
        <td>416 Запрошенный диапазон не удовлетворяется</td>
        <td>Клиент запросил часть файла, но сервер не может предоставить эту часть</td>
    </tr>
    <tr>
        <td>417 Ожидание не удалось</td>
        <td>Сервер не может удовлетворить требования поля ожидать заголовок запроса</td>
    </tr>
</table>

<h3 id="подраздел-4.5">5xx: ошибка сервера <a href="#top">↑top↑</a></h3>

<table>
    <tr>
        <th>Сообщение</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>500 Внутренняя ошибка сервера</td>
        <td>Общее сообщение об ошибке, если более конкретное сообщение не подходит</td>
    </tr>
    <tr>
        <td>501 Не реализовать</td>
        <td>Сервер не распознает метод запроса и не имеет возможности исполнить просьбу</td>
    </tr>
    <tr>
        <td>502 Плохой шлюз</td>
        <td>Сервер, действуя в качестве шлюза или прокси сервера, получил недопустимый ответ от вышестоящего сервера</td>
    </tr>
    <tr>
        <td>503 Служба недоступна</td>
        <td>Сервер в данный момент недоступен (перегружен или не работает)</td>
    </tr>
    <tr>
        <td>504 Время ожидания шлюза</td>
        <td>Сервер действовал как шлюз или прокси и не получил своевременного ответа от вышестоящего сервера</td>
    </tr>
    <tr>
        <td>505 Версия HTTP не поддерживается</td>
        <td>Сервер не поддерживает версию протокола HTTP, используемую в запросе</td>
    </tr>
    <tr>
        <td>511 Требуется сетевая аутентификация</td>
        <td>Клиент должен аутентифицироваться для получения доступа к сети</td>
    </tr>
</table>

---

<!-- Contacts -->
<h2>📡 Контакты автора:</h2>
<div id="badges" align="center">
    <a href="https://vk.com/bogdan_klimov">
        <img src="https://img.shields.io/badge/VK-blue?style=for-the-badge&logo=vk&logoColor=white&size=30" alt="VK Badge"/>
    </a> &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://t.me/bogdanklimov">
        <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"/>
    </a> &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.instagram.com/ghost_777_24?igsh=aHdwa2s1cTIzbmhw&utm_source=qr">
        <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white" alt="Instagram Badge"/>
    </a> &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.facebook.com/profile.php?id=100033935590093&mibextid=LQQJ4d">
        <img src="https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white" alt="Facebook Badge"/>
    </a>
</div>
