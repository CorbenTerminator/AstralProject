Для скачивание проекта необходимо выполнить команду:
```
git clone https://github.com/CorbenTerminator/AstralProject.git
```
Данный репозиторий является git submodule, 
поэтому после скачивания проекта необходимо перейти в директорию и ввести следующие команды:
```
    git submodule init
    git submodule update
```
Для запуска проекта используется команда:
```
    docker-compose up
```
После запуска всех контейнеров можно перейти по адресу http://localhost/login
