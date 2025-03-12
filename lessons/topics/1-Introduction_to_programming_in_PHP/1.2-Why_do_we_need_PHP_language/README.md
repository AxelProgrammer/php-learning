<div align="right">
   <strong>🌍 English Text</strong>
</div><br>  

To view Markdown files as formatted text, go to **[MD Preview Launch Guide](https://github.com/AxelProgrammer/php-learning/blob/master/lessons/manual.md)** in the **lessons** folder. 

# 1.2 PHP Language: What is it Used For and What Does it Look Like

## What is PHP?

PHP (Hypertext Preprocessor) is one of the most popular programming languages ​​for web development. It was created by Rasmus Lerdorf in 1994 and has been actively developed since then. PHP is a server-side language, which means that the code is executed on the server side, not in the user's browser. This allows you to create dynamic web pages that can change depending on the data received from the user or from a database.

## What is PHP Used For?

PHP is used to solve many problems in web development. Here are the main ones:

1. **Creating Dynamic Web Pages**
PHP allows you to generate HTML code based on data received from the user or from a database. For example, you can display different pages depending on the user's login.

2. **Form Data Processing**
PHP can process data submitted by the user via HTML forms (e.g. registration, authorization, sending messages).

3. **Database Interaction**
PHP is often used to work with databases such as MySQL, PostgreSQL, SQLite and others. This allows you to store and retrieve data necessary for the operation of the web application.

4. **Web Application Creation**
PHP can be used to create complex web applications such as blogs, online stores, forums, content management systems (CMS) and more. Popular CMS such as WordPress, Joomla and Drupal are written in PHP.

5. **API and Third-Party Integration**
PHP allows you to interact with external APIs (e.g. payment systems, social networks, email services) to extend the functionality of web applications.

6. **Working with files on the server**
PHP can create, read, write, and delete files on the server, which is useful for working with user data, logs, and other files.

## What does PHP code look like?

PHP code is embedded in an HTML document using special tags `<?php ... ?>`. This allows you to mix PHP code with HTML to create dynamic pages. Here is an example of a simple PHP script:

```php
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Пример PHP-кода</title>
</head>
<body>
    <h1>Привет, мир!</h1>
    <?php
        // This is a single-line comment in PHP
        /*
         This is a multi-line comment.
         It can span multiple lines.
        */
        $name = "World"; // Create a variable $name and assign it the value "World"
        echo "<p>Hello, $name!</p>"; // Output text using the variable
    ?>
</body>
</html>
```
## Detailed explanation of tags and code

### 1. Basic HTML structure
HTML (HyperText Markup Language) is a markup language that is used to create the structure of a web page. The following tags are used in this task:

- **`<!DOCTYPE html>`**
This tag tells the browser that the document is written in HTML5. It must be the first line in any HTML document.

- **`<html>`**
The main container for all page content. Everything inside this tag is considered part of the HTML document.

- **`<head>`**
This section contains meta information about the page, such as the title, encoding, links to styles and scripts. Inside the `<head>` is:
- **`<meta charset="UTF-8">`**
Specifies the encoding of the document (UTF-8 supports Cyrillic and other characters).
- **`<title>`**
The page title that is displayed in the browser tab.

- **`<body>`**
This section contains all the content of the page that is displayed in the browser: text, images, links, etc.

### 2. Adding PHP code
PHP code is embedded in HTML using special tags `<?php ... ?>`. Any PHP code can be written inside these tags.

- **`<?php`**
The opening PHP tag. It tells the server that PHP code follows.

- **`// This is a single-line comment in PHP`**
Comments in PHP are used to explain the code. They are ignored by the interpreter and do not affect the execution of the program. Single-line comments begin with `//`.

- **`/* ... */`**
Multi-line comments begin with `/*` and end with `*/`. They can occupy several lines.

- **`$name = "World";`**
In PHP, variables begin with the `$` symbol. In this case, the variable `$name` is created and assigned the value `"World"`.

- **`echo "<p>Hello, $name!</p>";`**
The `echo` function is used to output text or HTML code. In this case, the paragraph `<p>` with the text "Hello, World!" is output. The variable `$name` is substituted into the string.

- **`?>`**
The closing PHP tag. It tells the server that the PHP code has ended.

<div align="right">
   <strong>🌍 Текст на русском</strong>
</div><br>  

Чтобы просмотреть Markdown-файлы в виде отформатированного текста, перейдите в **[Инструкцию по запуску MD Preview](https://github.com/AxelProgrammer/php-learning/blob/master/lessons/manual.md)** в папке **lessons**. В этой инструкции вы найдёте подробное руководство по использованию различных инструментов для просмотра и редактирования Markdown-файлов.

# 1.2 Язык PHP: для чего используется и как выглядит

## Что такое PHP?

PHP (Hypertext Preprocessor) — это один из самых популярных языков программирования для веб-разработки. Он был создан Расмусом Лердорфом в 1994 году и с тех пор активно развивается. PHP является серверным языком, что означает, что код выполняется на стороне сервера, а не в браузере пользователя. Это позволяет создавать динамические веб-страницы, которые могут изменяться в зависимости от данных, полученных от пользователя или из базы данных.

## Для чего используется PHP?

PHP используется для решения множества задач в веб-разработке. Вот основные из них:

1. **Создание динамических веб-страниц**  
   PHP позволяет генерировать HTML-код на основе данных, полученных от пользователя или из базы данных. Например, можно отображать разные страницы в зависимости от логина пользователя.

2. **Обработка данных форм**  
   PHP может обрабатывать данные, отправленные пользователем через HTML-формы (например, регистрация, авторизация, отправка сообщений).

3. **Взаимодействие с базами данных**  
   PHP часто используется для работы с базами данных, такими как MySQL, PostgreSQL, SQLite и другими. Это позволяет хранить и извлекать данные, необходимые для работы веб-приложения.

4. **Создание веб-приложений**  
   С помощью PHP можно создавать сложные веб-приложения, такие как блоги, интернет-магазины, форумы, системы управления контентом (CMS) и многое другое. Популярные CMS, такие как WordPress, Joomla и Drupal, написаны на PHP.

5. **Интеграция с API и сторонними сервисами**  
   PHP позволяет взаимодействовать с внешними API (например, платежные системы, социальные сети, почтовые сервисы) для расширения функциональности веб-приложений.

6. **Работа с файлами на сервере**  
   PHP может создавать, читать, записывать и удалять файлы на сервере, что полезно для работы с пользовательскими данными, логами и другими файлами.

## Как выглядит PHP-код?

PHP-код встраивается в HTML-документ с использованием специальных тегов `<?php ... ?>`. Это позволяет смешивать PHP-код с HTML для создания динамических страниц. Вот пример простого PHP-скрипта:

```php
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Пример PHP-кода</title>
</head>
<body>
    <h1>Привет, мир!</h1>
    <?php
        // Это однострочный комментарий в PHP
        /*
            Это многострочный комментарий.
            Он может занимать несколько строк.
        */
        $name = "Мир"; // Создаем переменную $name и присваиваем ей значение "Мир"
        echo "<p>Привет, $name!</p>"; // Выводим текст с использованием переменной
    ?>
</body>
</html>
```

## Подробное объяснение тегов и кода

### 1. Базовая HTML-структура
HTML (HyperText Markup Language) — это язык разметки, который используется для создания структуры веб-страницы. В задании используются следующие теги:

- **`<!DOCTYPE html>`**  
  Этот тег указывает браузеру, что документ написан на HTML5. Он должен быть первой строкой в любом HTML-документе.

- **`<html>`**  
  Основной контейнер для всего содержимого страницы. Всё, что находится внутри этого тега, считается частью HTML-документа.

- **`<head>`**  
  Этот раздел содержит метаинформацию о странице, такую как заголовок, кодировка, ссылки на стили и скрипты. Внутри `<head>` находится:
  - **`<meta charset="UTF-8">`**  
    Указывает кодировку документа (UTF-8 поддерживает кириллицу и другие символы).
  - **`<title>`**  
    Заголовок страницы, который отображается на вкладке браузера.

- **`<body>`**  
  В этом разделе находится всё содержимое страницы, которое отображается в браузере: текст, изображения, ссылки и т.д.

### 2. Добавление PHP-кода
PHP-код встраивается в HTML с помощью специальных тегов `<?php ... ?>`. Внутри этих тегов можно писать любой PHP-код.

- **`<?php`**  
  Открывающий тег PHP. Он указывает серверу, что дальше идёт PHP-код.

- **`// Это однострочный комментарий в PHP`**  
  Комментарии в PHP используются для пояснения кода. Они игнорируются интерпретатором и не влияют на выполнение программы. Однострочные комментарии начинаются с `//`.

- **`/* ... */`**  
  Многострочные комментарии начинаются с `/*` и заканчиваются `*/`. Они могут занимать несколько строк.

- **`$name = "Мир";`**  
  В PHP переменные начинаются с символа `$`. В данном случае создаётся переменная `$name`, которой присваивается значение `"Мир"`.

- **`echo "<p>Привет, $name!</p>";`**  
  Функция `echo` используется для вывода текста или HTML-кода. В данном случае выводится абзац `<p>` с текстом "Привет, Мир!". Переменная `$name` подставляется в строку.

- **`?>`**  
  Закрывающий тег PHP. Он указывает серверу, что PHP-код закончился.
