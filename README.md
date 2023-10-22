# moduleE4_homework

Если Docker не установлен, то установливаем его командой: `curl -fsSL https://get.docker.com/ | sh`  
и Compose : `sudo apt  install docker-compose`


После установки docker, загружаем проект :
`git clone https://github.com/Ivan-Gormatov/moduleE4_homework.git`


Переходим в директорию проекта:
`cd moduleE4_homework`  
и запускаем :
`docker-compose up -d` 

django доступен по адресу `http://localhost:1337` (порт можно изменить в файле docker-compose.yml) 

Войти на страницу администрирования можно по адресу:
`http://localhost:1337/admin`   
`login: admin`
`password: admin`
