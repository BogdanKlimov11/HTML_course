<h1 id="top">Список тегов HTML</h1>

---

<!-- Оглавление -->
<h2>Оглавление</h2>
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
<h2 id="!">! <a href="#top">↑top↑</a></h2>

`<!DOCTYPE>`

**Описание**

Элемент `<!DOCTYPE>` предназначен для указания типа текущего документа 
— DTD (document type definition, описание типа документа). Это необходимо, 
чтобы браузер понимал, как следует интерпретировать текущую веб-страницу, 
поскольку HTML существует в нескольких версиях, кроме того, имеется XHTML 
(EXtensible HyperText Markup Language, расширенный язык разметки 
гипертекста), похожий на HTML, но различающийся с ним по синтаксису. 
Чтобы браузер «не путался» и понимал, согласно какому стандарту отображать 
веб-страницу и необходимо в первой строке кода задавать <!DOCTYPE>.

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

* Нет.

---

<h2 id="A">A <a href="#top">↑top↑</a></h2>

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
