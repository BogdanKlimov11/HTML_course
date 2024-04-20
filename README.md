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

---

<!-- Теги по алфавиту -->
<h2 id="раздел-2">Теги по категориям <a href="#top">↑top↑</a></h2>

Здесь расположены все теги по категориям. Полный список с подробным описанием и расположенным в 
алфавитном порядке можно найти в разделе <a href="подраздел-2.13">"Полный список тегов"</a>

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

<h3 id="подраздел-2.10">Теги стиля и семантики <a href="#top">↑top↑</a></h3>

<h3 id="подраздел-2.11">Теги мета информации <a href="#top">↑top↑</a></h3>

<h3 id="подраздел-2.12">Теги программирования <a href="#top">↑top↑</a></h3>

<h3 id="подраздел-2.13">Полный список тегов <a href="#top">↑top↑</a></h3>

Теги с полным описанием и в алфавитном порядке можно взять <a href="https://github.com/BogdanKlimov11/HTML_course/blob/main/Resources/Tags.md">здесь</a>.

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
