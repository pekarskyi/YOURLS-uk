# YOURLS-uk

Українська локалізація для [YOURLS](https://github.com/YOURLS/YOURLS) 1.9.2<br>
Сайт: [yourls.org](https://yourls.org/)

![GitHub release (latest by date)](https://img.shields.io/github/v/release/pekarskyi/YOURLS-uk?style=for-the-badge)

Кількість рядків: 303<br>
Дата оновлення: 07-03-2023

## Встановлення локалізації

1. Завантажте архів (зелена кнопка зверху праворуч Code -> Download ZIP) і розпакуйте його.
2. Помістіть файл <strong>uk.mo</strong> в папку <strong>/user/languages/</strong>
3. Відкрийте файл /user/config.php в редакторі і в рядку 46 вкажіть як тут:

```php
define( 'YOURLS_LANG', 'uk' );
```
4. Перевірте наявність української мови в панелі адміністратора.

## Як оновити локалізацію?

1. Завантажте нову версію у вигляді архіву, розпакуйте.
2. Помістіть файл <strong>uk.mo</strong> в папку <strong>/user/languages/</strong>

## FAQ

1. Навіщо потрібен файл uk.po?

Він потрібен для редагування перекладу. З цим файлом працює людина (а з файлом .MO машина-сервер). 

Як редагувати файл .PO?
На комп'ютері це можна зробити за допомогою безкоштовної програми [Poedit](http://www.poedit.net/).
Після внесення і збереження змін у файлі .PO згенерується новий файл .MO. Цей файл завантажте на свій сайт.

## Пропозиції

Питання та пропозиції залишайте [тут](https://github.com/Dizer7/YOURLS-uk/issues). Дякую!

[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://sitex.me/standwithukraine)
