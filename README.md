<h1>Справочник по языку программирования HTML</h1>

---

<!-- Оглавление -->
<h2>Оглавление</h2>
<nav>
    <ol>
        <li><a href="#раздел-1">Учебник</a></li>
        <ul>
            <li><a href="#подраздел-1.1">Введение</a></li>
            <li><a href="#подраздел-1.2">Редактор</a></li>
            <li><a href="#подраздел-1.3">some</a></li>
        </ul>
        <li><a href="#раздел-2">Формы</a></li>
        <ul>
            <li><a href="#подраздел-2.1">some</a></li>
            <li><a href="#подраздел-2.2">some</a></li>
            <li><a href="#подраздел-2.3">some</a></li>
        </ul>
        <li><a href="#раздел-3">Графика</a></li>
        <ul>
            <li><a href="#подраздел-3.1">some</a></li>
            <li><a href="#подраздел-3.2">some</a></li>
            <li><a href="#подраздел-3.3">some</a></li>
        </ul>
        <li><a href="#раздел-4">Медиа</a></li>
        <ul>
            <li><a href="#подраздел-4.1">some</a></li>
            <li><a href="#подраздел-4.2">some</a></li>
            <li><a href="#подраздел-4.3">some</a></li>
        </ul>
    </ol>
</nav>

---

<!-- Разделы -->
<h2 id="раздел-1">Учебник</h2>

<h3 id="подраздел-1.1">Введение</h3>

**HTML** - это стандартный язык разметки для создания Веб страниц.

<h4>Что такое HTML?</h4>

* HTML - расшифровывается как Гипертекстовый Язык Разметки
* HTML - код описывает структуру веб страниц с помощью разметки
* HTML - элементы являются строительными блоками страниц HTML
* HTML - элементы представляют теги
* HTML - теги содержат, "Заголовок", "Параграф", "Таблицы" и т.д.
* Браузеры не отображают теги HTML, они используют их для вывода содержимого страницы

<h4>Простой документ HTML</h4>

**Пример**

```html
<!DOCTYPE html>
<html>
    <head>
        <title>HTML пример</title>
    </head>
    <body>
        <h1>Мой первый заголовок</h1>
        <p>Мой первый параграф.</p>
    </body>
</html>
```

**Объяснение примера**

* `<!DOCTYPE html>` - декларация, определяет документ HTML5
* `<html>` - элемент, является корневым элементом HTML страницы
* `<head>` - элемент, содержит метаинформацию о документе
* `<title>` - элемент, задает заголовок документа
* `<body>` - элемент, содержит видимый контент страницы
* `<h1>` - элемент, определяет большой заголовок
* `<p>` - элемент, определяет параграф

<h4>Что такое элемент HTML?</h4>

HTML элемент определяется начальным тегом, некоторым содержимым и конечным тегом:

```html
<tagname>Контент находится здесь...</tagname>
```

HTML элемент это все от начального тега до конечного тега:

```html
<h1>Мой первый заголовок</h1>
```

```html
<p>Мой первый параграф</p>
```

<table>
    <tr>
        <th>Начальный тег</th>
        <th>Содержимое элемента</th>
        <th>Конечный тег</th>
    </tr>
    <tr>
        <td>&#60;h1&#62;</td>
        <td>Мой первый заголовок</td>
        <td>&#60;/h1&#62;</td>
    </tr>
    <tr>
        <td>&#60;p&#62;</td>
        <td>Мой первый параграф</td>
        <td>&#60;/p&#62;</td>
    </tr>
    <tr>
        <td>&#60;br&#62;</td>
        <td>нет</td>
        <td>нет</td>
    </tr>
</table>

**Примечание**

Некоторые HTML элементы не имеют содержимого (например, элемент &#60;br&#62;). Эти элементы называются пустыми элементами. Пустые элементы 
не имеют конечного тега!

<h4>Веб браузеры</h4>

Цель веб-браузеров (Chrome, IE, Firefox, Safari) - чтения HTML документов и их отображения.

Браузер не отображает HTML теги, он использует их, чтобы определить, как отобразить документ:

<img src="https://github.com/BogdanKlimov11/HTML_course/assets/136115919/d96f4dfe-aacc-4107-810a-b80789787292" width="50%" height="auto">

<h4>Структура страницы HTML</h4>

Ниже представлена визуализация структуры страницы HTML:

<img src="https://github.com/BogdanKlimov11/HTML_course/assets/136115919/b744a0dc-0b02-43a5-b424-2d5377281b16" width="50%" height="auto">

**Примечание**

Содержание находящаяся внутри &#60;body&#62; (в белой секции выше), будет отображаться в браузере.

<h4>История</h4>

С первых дней существования Всемирной паутины существовало множество версий HTML:

<table>
    <tr>
        <th>Год</th>
        <th>Версия</th>
    </tr>
    <tr>
        <td>1989</td>
        <td>Тим Бернерс-Ли изобрел www</td>
    </tr>
    <tr>
        <td>1991</td>
        <td>Тим Бернерс-Ли изобрел HTML</td>
    </tr>
    <tr>
        <td>1993</td>
        <td>Дэйв Раггетт составлен в формате HTML+</td>
    </tr>
    <tr>
        <td>1995</td>
        <td>HTML рабочая группа определила HTML 2.0</td>
    </tr>
    <tr>
        <td>1997</td>
        <td>W3C рекомендация: HTML 3.2</td>
    </tr>
    <tr>
        <td>1999</td>
        <td>W3C рекомендация: HTML 4.01</td>
    </tr>
    <tr>
        <td>2000</td>
        <td>W3C рекомендация: XHTML 1.0</td>
    </tr>
    <tr>
        <td>2008</td>
        <td>WHATWG HTML5 первый публичный проект</td>
    </tr>
    <tr>
        <td>2012</td>
        <td><a href="https://html.spec.whatwg.org/multipage/">WHATWG HTML5 Существующий стандарт</a></td>
    </tr>
    <tr>
        <td>2014</td>
        <td><a href="http://www.sw3.org/TR/html5/">W3C Рекомендация: HTML5</a></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>W3C Рекомендация Кандидата: HTML 5.1</td>
    </tr>
    <tr>
        <td>2017</td>
        <td><a href="http://www.sw3.org/TR/html51/">W3C Рекомендация: HTML5.1 2nd Edition</a></td>
    </tr>
    <tr>
        <td>2017</td>
        <td><a href="http://www.sw3.org/TR/html52/">W3C Рекомендация: HTML5.2</a></td>
    </tr>
</table>

<h3 id="подраздел-1.2">Редактор</h3>

**Простой текстовый редактор** - это все, что вам нужно для изучения HTML.

<h4>Изучайте HTML с помощью Notepad или TextEdit</h4>

Веб страницы могут быть созданы и изменены с помощью профессиональных редакторов HTML.

Однако, для изучения HTML мы рекомендуем простой текстовый редактор, например Notepad++ (PC) или TextEdit (Mac).

Мы верим, что простой текстовый редактор - это очень хороший способ выучить HTML.

Выполните следующие действия ниже, чтобы создать свою первую веб-страницу с Notepad или TextEdit.

<h4>Шаг 1: Открыть Notepad++</h4>

Windows 8 или старых версий:

Открыть стартовый экран (символ в окне внизу слева на экране). Тип Notepad++.

Windows 7 или новых версий:

Открыть Пуск > Все программы > Аксессуары > Notepad++

<h4>Шаг 1: Открыть TextEdit (Mac)</h4>

Открыть Пуск > Приложения > TextEdit

Также изменить некоторые параметры, чтобы получить приложение правильно сохранить файлы. В Предпочтения > Формат > выбрать "Обычный Текст"

Затем под "Открыть и сохранить", установите флажок, который говорит "Игнорировать форматированного текста команды в HTML-файлах".

**Затем откройте новый документ, чтобы поместить код.**

<h4>Шаг 2: Написать HTML</h4>

Напишите или скопируйте HTML в блокноте.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Моя первая страница</title>
    </head>
    <body>
        <h2>Это заголовок</h2>     
        <p>Это параграф.</p>
    </body>
</html>
```

<img src="https://github.com/BogdanKlimov11/HTML_course/assets/136115919/e0679f35-fde8-42fe-875f-0a3c39b09b98" width="50%" height="auto">

<h3 id="подраздел-1.3">some</h3>
    <p>. . .</p>

---

<h2 id="раздел-2">Формы</h2>
    <p>. . .</p>

<h3 id="подраздел-2.1">some</h3>
    <p>. . .</p>

<h3 id="подраздел-2.2">some</h3>
    <p>. . .</p>

<h3 id="подраздел-2.3">some</h3>
    <p>. . .</p>

---

<h2 id="раздел-3">Графика</h2>
<p>. . .</p>

<h3 id="подраздел-3.1">some</h3>
    <p>. . .</p>

<h3 id="подраздел-3.2">some</h3>
    <p>. . .</p>

<h3 id="подраздел-3.3">some</h3>
    <p>. . .</p>

---

<h2 id="раздел-4">Медиа</h2>
<p>. . .</p>

<h3 id="подраздел-4.1">some</h3>
    <p>. . .</p>

<h3 id="подраздел-4.2">some</h3>
    <p>. . .</p>

<h3 id="подраздел-4.3">some</h3>
    <p>. . .</p>

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
