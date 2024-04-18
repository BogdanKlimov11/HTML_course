<h1>Справочник по языку разметки HTML</h1>

---

<!-- Оглавление -->
<h2>Оглавление</h2>
<nav>
    <ol>
        <li><a href="#раздел-1">Введение</a></li>
        <li><a href="#раздел-2">Инструментарий</a></li>
        <li><a href="#раздел-3">Теги</a></li>
        <ul>
            <li><a href="#подраздел-3.1">Парные теги</a></li>
            <li><a href="#подраздел-3.2">Правила применения тегов</a></li>
            <li><a href="#подраздел-3.3">Атрибуты тегов</a></li>
        </ul>
        <li><a href="#раздел-4">Типы тегов</a></li>
        <ul>
            <li><a href="#подраздел-4.1">Теги верхнего уровня</a></li>
            <li><a href="#подраздел-4.2">Теги заголовка документа</a></li>
            <li><a href="#подраздел-4.3">Блочные элементы</a></li>
            <li><a href="#подраздел-4.4">Строчные элементы</a></li>
            <li><a href="#подраздел-4.5">Универсальные элементы</a></li>
            <li><a href="#подраздел-4.6">Теги для списков</a></li>
            <li><a href="#подраздел-4.7">Теги для таблиц</a></li>
            <li><a href="#подраздел-4.8">Теги для фреймов</a></li>
        </ul>
        <li><a href="#раздел-5">Значения атрибутов тегов</a></li>
        <ul>
            <li><a href="#подраздел-5.1">Цвет</a></li>
            <li><a href="#подраздел-5.2">Размер</a></li>
            <li><a href="#подраздел-5.3">Адрес</a></li>
        </ul>
        <li><a href="#раздел-6">Текст</a></li>
        <ul>
            <li><a href="#подраздел-6.1">Абзацы</a></li>
            <li><a href="#подраздел-6.2">Заголовки</a></li>
            <li><a href="#подраздел-6.3">Выравнивание текста</a></li>
            <li><a href="#подраздел-6.4">Начертание</a></li>
            <li><a href="#подраздел-6.5">Верхний и нижний индексы</a></li>
            <li><a href="#подраздел-6.6">Спецсимволы</a></li>
        </ul>
        <li><a href="#раздел-7">Ссылки</a></li>
        <ul>
            <li><a href="#подраздел-7.1">Абсолютные и относительные ссылки</a></li>
            <li><a href="#подраздел-7.2">Виды ссылок</a></li>
            <li><a href="#подраздел-7.3">Правила вложений для тега &#60;a&#62;</a></li>
            <li><a href="#подраздел-7.4">Атрибуты ссылок</a></li>
            <li><a href="#подраздел-7.5">Ссылка на адрес электронной почты</a></li>
        </ul>
        <li><a href="#раздел-8">Якоря</a></li>
        <li><a href="#раздел-9">Изображения</a></li>
        <ul>
            <li><a href="#подраздел-9.1">Форматы файлов</a></li>
            <li><a href="#подраздел-9.2">Добавление рисунка</a></li>
            <li><a href="#подраздел-9.3">Альтернативный текст</a></li>
            <li><a href="#подраздел-9.3">Изменение размеров рисунка</a></li>
        </ul>
        <li><a href="#раздел-10">Списки</a></li>
        <ul>
            <li><a href="#подраздел-10.1">Маркированный список</a></li>
            <li><a href="#подраздел-10.2">Нумерованный список</a></li>
            <li><a href="#подраздел-10.3">Список определений</a></li>
        </ul>
        <li><a href="#раздел-11">Таблицы</a></li>
        <ul>
            <li><a href="#подраздел-11.1">Атрибуты тега &#60;table&#62;</a></li>
            <li><a href="#подраздел-11.2">Атрибуты тега &#60;td&#62;</a></li>
            <li><a href="#подраздел-11.3">Особенности таблиц</a></li>
            <li><a href="#подраздел-11.4">Выравнивание таблиц</a></li>
            <li><a href="#подраздел-11.5">Объединение ячеек</a></li>
            <li><a href="#подраздел-11.6">Вложенные таблицы</a></li>
            <li><a href="#подраздел-11.7">Заголовок таблицы</a></li>
        </ul>
        <li><a href="#раздел-12">Фреймы</a></li>
        <ul>
            <li><a href="#подраздел-12.1">Создание фреймов</a></li>
            <li><a href="#подраздел-12.2">Ссылки во фреймах</a></li>
            <li><a href="#подраздел-12.3">Границы между фреймами</a></li>
            <li><a href="#подраздел-12.4">Изменение размеров фреймов</a></li>
            <li><a href="#подраздел-12.5">Полосы прокрутки</a></li>
            <li><a href="#подраздел-12.6">Плавающие фреймы</a></li>
        </ul>
        <li><a href="#раздел-13">Валидация документов</a></li>
        <ul>
            <li><a href="#подраздел-13.1">Проверка данных на валидность</a></li>
            <li><a href="#подраздел-13.2">Написание корректного кода</a></li>
            <li><a href="#подраздел-13.3">Исправление ошибок</a></li>
        </ul>
    </ol>
</nav>

---

<!-- Разделы -->
<h2 id="раздел-1">Введение</h2>

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
