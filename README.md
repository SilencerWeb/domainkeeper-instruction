# Инструкция к проекту DomainKeeper

[Инструкция на русском](https://github.com/SilencerWeb/domainkeeper-guide/blob/master/Russian.md)

Для начала нужно определиться с версий: *build*(папка `build`) или *inline*(папка `inline`)? Чтобы понять какая именно вам нужна, вам нужно задать один вопрос: Вы собираетесь изменять стили(CSS) и/или скрипты(JS)? Если да, то выбирайте *build*, в противном же случае выбирайте *inline*. К тому же, *inline* более оптимизирована чем build, поэтому мы рекомендуем использовать именно ее.

> Для того чтобы внести какие-либо изменения нужно открыть нужный вам файл с помощью текстового редактора(например, [Sublime text 3](https://www.sublimetext.com/3) или [Nodepad++](https://notepad-plus-plus.org/)). Для поиска нужной вам строки используйте сочетание клавиш CTRL + F на Windows и CMD + F на MacOS. Также после всех внесенных вами изменений нужно сохранить файл.


## Настройка отправки писем с сайта

1. Зарегистрируйте новый [Google-аккаунт](https://accounts.google.com/SignUp?hl=ru).
2. Откройте файл `mail.php`, который находится в папке `server` с помощью текстового редактора.
3. Найдите строку, в которой есть `Google account email`.
4. Замените `Google account email` на адрес почты зарегистрированного вами Google-аккаунта.
5. Найдите строку, в которой есть `Google account password`.
6. Замените `Google account password` на пароль зарегистрированного вами Google-аккаунта.
7. Найдите строку, в которой есть `To who email`.
8. Замените `To who email` на адрес почты, куда вы хотите получать сообщения с сайта.


## FAQ по отправке писем с сайта
> Для того чтобы внести какие-либо изменения нужно открыть `mail.php`, который находится в папке `server` с помощью текстового редактора.

### Как изменить имя отправителя?
1. Найти строку, в которой есть `From who name`.
2. Заменить `From who name` на нужное вам имя отправителя.

### Как изменить тему сообщения?
1. Найти строку, в которой есть `Subject text`.
2. Заменить `Subject text` на нужную вам тему сообщения.


## FAQ по изменению HTML-страниц
> Для того чтобы внести какие-либо изменения нужно открыть нужную вам HTML-страницу с помощью текстового редактора.

### Как изменить адрес почты?
  1. Найти все строки, в которых есть `example@gmail.com`.
  2. Заменить `example@gmail.com` на нужный вам адрес почты.
   
### Как изменить номер телефона?
  1. Найти все строки, в которых есть `7861234567`.
  2. Заменить `7861234567` на нужный вам номер телефона.
   
### Как изменить какой-либо текст?
  1. Найти нужный вам текст.
  2. Заменить его.
  
### Как изменить адрес ссылки?
  1. Найти нужную вам ссылку.
  2. Заменить значение атрибута `href` на нужную вам ссылку.
