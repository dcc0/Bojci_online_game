Игра Бойцы Онлайн с чатом OpenChatPhp

Установка
1) Закачайте файлы на сервер
2) Отредактируйте chat/conf/Class_Connect.php и ./config.php
3) Переименуйте _htaccess в .htaccess
Сервер должен поддерживать mod rewrite
4) База данных в chat.sql. Загрузите через phpmyadmin
5) Пароль можно задать в строке в файле: OpenChatPhp/chat/lib/Class_Send_Messages.php, строка номер: 80
6) Количество комнат чата можно отредактировать в файле: OpenChatPhp/chat/lib/view/Class_ListChannels.php, 
строка номер 30 -  "chat LIMIT 100". 
7) В conf/Class_Connect.php теперь можно настроить пароль для создания канала.
8) Количество всех сообщений чата настраивается
в файле lib/Class_Count_Delete_Messages.php, строка 60
9) Выделение текста жирным, курсивом или цветом
с помощью следующего кода: b->жирный, i->курсив,
color->red->красный текст.

Installaton
1) Upload files to your server
2) Edit chat/conf/Class_Connect.php
3) Raname _htaccess to .htaccess
Server must support ModRewrite
4) chat.sql is database example. You can use phpmyadmin for import
5) You can add a password in a file з phpmyadmin
5) Пароль можно задать в строке в файле: OpenChatPhp/chat/lib/Class_Send_Messages.php, line number 80
6) You can edit numbers of chat rooms in the following file: OpenChatPhp/chat/lib/view/Class_ListChannels.php,
line number 30 - "chat LIMIT 100".  
7) In conf/Class_Connect.php you can set a password for  creating channels.
8) Number of all messges in lib/Class_Count_Delete_Messages.php
9) You can change text style, using the following code:b->bold, i->italic,
color->red->red text.
