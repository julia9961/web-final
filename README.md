> По всем вопросам, возникшим в процессе выполнения производственной практики, можно получить ответ,
отправив письмо на почту **[juliajulia.vasileva@gmail.com](juliajulia.vasileva@gmail.com)**. В теме письма написать Web-final и ФИО.

# Создание веб-сайта с помощью HTML, CSS и сторонних библиотек

Содержание:
* [Описание производственной практики](#Описание-производственной-практики)
* [Задания](#задания)
    * [Написание технического задания](##Написание-технического-задания)
    * [Создание веб-сайта](##Создание-веб-сайта)
    * [Подготовка отчётности по производственной практике](##Подготовка-отчётности-по-производственной-практике)


## Описание производственной практики
В рамках производственной практики предлагается разработать веб-сайт.
Тематика веб-сайта определяется самостоятельно.
Разрешается выбрать внешний вид и тематику на основе уже существующего веб-сайта
(при этом подразумевается не создание копии, а некоего производного продукта).

При создании веб-сайтов часто возникают ситуации, в которых приходится заново решать одни и те же задачи. 
Чтобы избежать этой рутины, разработчики создают библиотеки - набор кода, который решает типичные задачи.
Эти библиотеки значительно упрощают и ускоряют создание веб-сайтов любой сложности. 
Они довольно популярны и используются веб-студиями по всему миру.
В работе приветствуется использование, таких библиотек, как: Vue.js, Bootstrap, Animate.css и другие.

Общий вид физической структуры веб-сайта:

```
┬(корневой каталог проекта)
├── assets
│   ├── images
│       └── (медиафайлы)
│   └── styles
│       └── main.css
│       └──(прочие файлы стилей)
├── pages
│   └── (прочие страницы веб-сайта)
├── scripts
│   └── (файлы скриптов)
└── index.html
```

## Задания

### Написание технического задания

Написать техническое задание, в котором указать:

- описание тематики веб-сайта,
- перечень страниц веб-сайта с описанием их содержимого.

Обязательно наличие следующих страниц:

- домашняя страница сайта, содержащая общее описание продукта (продуктов) компании, его преимущества по сравнению с аналогами, и особенности функционала;
- страница новостей компании (блог), содержащая новости и комментарии пользователей к ним;
- страница с описанием компании, списком сотрудников.

Помимо вышеуказанных страниц в веб-сайт необходимо добавить еще несколько страниц.

ТЗ должно подробно и недвусмысленно описывать требования, предъявляемые к веб-сайту, и его внешний вид. 
ТЗ и готовый проект не должны противоречить друг другу, одно должно следовать из другого.

### Создание веб-сайта

Сверстать веб-сайт.
Картинки, видео и прочие медиафайлы поместить в папку assets/images.

Заглавную страницу веб-сайта `index.html` поместить в корневой каталог веб-сайта. Все прочие страницы веб-сайта поместить в папку `pages`. 
Для каждой страницы веб-сайта установить заголовок и указать иконку.
При создании HTML-документов использовать семантические элементы.

Блоки объявления CSS отделить от HTML-документов и вынести в отдельные файлы. Эти файлы поместить в папку `styles`. 
Общие для всех страниц веб-сайта стили вынести в отдельный файл `main.css`.

Реализовать поддержку адаптивного дизайна.

Для всех страниц добавить шапку и подвал. В шапке отобразить логотип компании или продукта, а также ссылки на страницы веб-сайта (навигационного меню). 
В подвале разместить контактные данные (инициалы и e-mail). Помимо указанной информации в шапку и подвал разрешается добавить любую другую информацию.


### Подготовка отчётности по производственной практике
Оформить следующие документы:

- отчёт по производственной практике,
- аттестационный лист по производственной практике,
- дневник производственной практики (см. шаблон).

Состав отчёта по производственной практике:

- титульный лист (см. [шаблон](https://docs.google.com/document/d/1QeA-_5Lopt79KRXSqEKAM_whYUzU-1JwPBz6PRzPelQ/edit?usp=sharing)),
- содержание,
- задание (на производственную практику),
- техническое задание,
- макеты (скриншоты всех макетов),
- контрольный пример (скриншоты всех страниц сайта),
- код программы

Страницы отчёта пронумеровать. Ко всем изображениям и листингам в отчёте добавить поясняющие подписи, например:

- *Рис. 3 - главная страница (вид для мобильных телефонов),*
- *Исх. код 1 - содержимое файла index.html.*
