# Первые шаги по освоениею HTML

##Инструкция по запуску проекта

1. Скачиваем Vagrant и VirtualBox

1. Клонируем репозиторий в удобную нам паппку с помощью команды:

        git clone git@github.com:memedealer/New-03-05.git
 1. Переходим в папку **cd New-03-05** 
 1. Запускаем Виртуальную машину: `vagrant up`
 1. Захожим в командную строку виртуальной машины по SSH-протоколу: vagrant ssh
 ## Инструкция по базовой работе с GIT
 
 1. `git add` - добавляет файл в индекс
 1. `git commit` - создает коммит из всех файлов в индексе 
 1. `git commit -m "Comment"` - позволяет добавить комментарий к коммиту в командной строке
 1. `git push` -  залить изменения в удаленный репозиторий
 1. `git pull` - принять изменения с удаленного репозитория 
 1. `git clone  git@github.com:useer/reponame.git` - склонировать удаленный репозиторий
 

 

<<<<<<< HEAD
 
 ## Работа с HTML
 
 ## Подключение скриптов и стилей
 
 * Скрипты можно подключить с помощью тега `<script>`:
         <script type ="text/javascript"> 
         // объясвляем переменную j и присваиваем 
         console.log(j);
         </script>
                  
 * Стили создаются с помощью тега `<style>`:                  
        <style></style>
        
 ## Подключение файлов
 
 * Чтобы подключить скриптовый файл, нелбходимо прописать тег `<script>` с атрибутом `src` `<script src=">` :
     <script src="/index.js" type="text/javascript"></script>
     
 * Для подключения файла со стилями прописываем тег `<link>` с атрибутом `rel="stylesheet"`:
        <link rel="stylesheet" href="index.css">
 
        
        
 ##
=======
1. `git add` - добавляет файл в индекс
1. `git commit` - создаёт коммит из всех файлов в индексе
1. `git commit -m "comment"`- позволяет добавить комментарий к коммиту в командной строке
1. `git push` - залить изменения в удалённый репозиторий
1. `git pull`-принять изменения с удалённого репозитория
1. ` git clone git@gitbush`


# Как настраивать Nginx-сервер
## Запуск, остановка, перезагрузка конфигурации


1. Чтобы запустить nginx, нужно выполнить исполняемый файл. Когда nginx запущен, им можно управлять, вызывая исполняемый файл с параметром -s. Используйте следующий синтаксис: `nginx -s сигнал`
1. Где сигнал может быть одним из следующих: 
`stop` — быстрое завершение
`quit` — плавное завершение
`reload` — перезагрузка конфигурационного файла
`reopen` — переоткрытие лог-файлов


# Как захостить сайт на GitHub Pages
## Чтобы захостить сайт нам нужно:


1. Первым делом нам нужно создать репозиторий
1. Вторым шагом будет загрузка всех необходимых файлов в наш репозиторий!
1. После загрузки файлов переходим по ссылке "username.github.io" в моём случае это "frogmister13.github.io" Вуаля, ваша HTML страница готова!
>>>>>>> dd28faae2a8405921e68a23308762e62638ffe7d
