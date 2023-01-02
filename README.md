# Запускаем Docker-контейнер с помощью jupiterhub:

## 1. Cначала необходимо запустить терминал и склонировать репозиторий, т.e. ввести в терминал строre ниже:
    git clone https://github.com/NightRunnerEB/docker-firstry.git
## 2. Теперь следует создать Docker-образец, используя команду:
    docker build -t <имя образа> <путь к образу (папка загрузки (Windows) или /Users/<username>(Mac))>/docker-firstry
## 3. Если вы не отпали на предыдущих этапах, то поздравляю, осталось ввести последнюю команду для запуска контейнера:
    docker run --name <имя контейнера> -p 80:8000 <имя образа>
