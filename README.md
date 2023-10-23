# moduleE4_homework

Добрый день <<Alisa Miller>>! Прошу Вас проверить мою дом. работу:

GitHub репозиторий:
https://github.com/muroshkin88/TEMP_E001


https://hub.docker.com/repository/docker/muroshkin88/my_project/general

username: dj

password: qwertyu1


Если Docker не установлен, то установливаем его командой: `curl -fsSL https://get.docker.com/ | sh`  
и Compose : `sudo apt  install docker-compose`


После установки docker, загружаем проект :

`git clone https://github.com/muroshkin88/TEMP_E001.git`


Переходим в директорию проекта:
`cd TEMP_E001`  
и запускаем :
`docker-compose up -d` 

django доступен по адресу `http://localhost:1337` (порт можно изменить в файле docker-compose.yml) 

Войти на страницу администрирования можно по адресу:
`http://localhost:1337/admin`   
`login: admin`
`password: admin`
