# ucsc-devops
<b>Инструкция по установке</b>
1. Устанавливаем необходимое ПО:<br>
`sudo apt-get update && sudo apt-get install -y docker docker.io docker-compose`
2. Добавляем пользователя в группу docker и применяем изменения:<br>
`sudo usermod -aG docker $USER && newgrp docker`
3. Клонируем репозиторий:<br>
` git clone https://github.com/artyomp1506/ucsc-devops`
4. Распаковываем архив:<br>
`cd ucsc-devops && tar -xaf nginx-php.tar.gz `
5. Запускаем контейнеры из docker-compose:<br>
`docker-compose up -d`
