sli
===

SLI - Site Language Injection

Текущая версия: 1.0 (Проверить обновления - http://sli.su/download/)<br>
Лицензия: Donationware <br>
Автор: Богдан Рыхаль (GANJAR) <br>
Сайт: http://sli.su/<br>

Продажа и публикация программы без согласия<br>
автора - запрещена.<br>
По всем вопросам пишите на Email: support@sli.su <br>

Требования:<br>
Apache, PHP 5.2 и выше, mod_rewrite, MySQL, Memcache (для быстрой работы приложения. Не обязательно), PDO, mbString, SimpleXML<br>
<br>
Установка:  <br>
1.  Залить файлы на сервер<br>
2.  Добавить в файл .htaccess который находится в корневой директории сайта строку<br>
    php_value auto_prepend_file "[full_path]/protected/sli.php"<br>
    Где [full_path] - полный пусть к директории с модулем.     <br>
    Если весь сайт работает через один контроллер - можно подключить модуль через include "[full_path]/protected/sli.php";<br>
3.  Выставить права 0777 на папку protected/data и на все внутренние директории<br>
4.  Открыть файл protected/config/config.php и прописать данные конекта к БД MySQL <br>
5.  Зайти в админку по адресу htt://адресСайта/sli/index.php<br>
6.  Ввести свой Email и пароль.<br>
7.  Войти под указанными данными<br>
<br>
Больше информации в разделе документация:
http://sli.su/documentation/<br>
