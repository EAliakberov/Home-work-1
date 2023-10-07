# Краткое изложение пройденного материала
## 1. Команды для работы с файловой системой
**pwd** (print worcking directory) - отображает путь к текущей рабочей папке GIT.  
**cd** (change directory) - с помощью этой команды можно изменить текущую рабочую папку на любую другую. Путь можно задавать относительный или абсолютный. С помощью особых названий можно попасть в родительсую папку - это ".." или указать на текущую папку с помощью одной точки ".", например, "../".  
**ls** (list) - отображает содержимое текущей папки, либо указанной папки. Чтобы отобразить содержимое папки, нужно после команды написать путь к ней, со всеми командами можно использовать симаолы "..", "~".
**mkdir** - создание директории. Можно создать сразу несколько директорий, с помощью флага *-p*.  
**touch** - создание файла  
**cp** - копирование файла. Сначала указывается файл, который нужно скопировать, потом новое расположение относительно текущего.  
**mv** - переместить файл. Работает аналогичным прошлой команде образом, только файл не копируется, а перемещается в новое расположение.  
**rm** - Удаление файла. Полное удаление файла, не перемещение в корзину!!!  
**rmdir** - удаление пустой директории. Удалить не пустую директорию нельзя, будет сообщено об ошибке. Для удаления папки, которая содержит файлы необходимо использовать предыдущую команду: **rm** с параметром **-r** (*recursive* - рекурсивно), удалить файлы содержащиеся в папке рекурсивно с последующим удаление самой папки).

## 2. Инициализация репозитория
**git init** - делает из папки проекта репозиторий, создает папку ".git" в которой содержатся необходимые для работы git файлы. Чтобы разгитить папку достаточно просто удалить из нее папку .git со всем содержимым. 
**git status** - команда для проверки состояния ".git". 