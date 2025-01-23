# Lab_3

#ЗАДАНИЕ1

[ссылка](https://hub.docker.com/repository/docker/magnet1155/custom-nginx/general) на репозиторий

#ЗАДАНИЕ2

* Для запуска контейнера с задаными характеристиками использовал команду

![Снимок экрана 2025-01-23 в 17 08 10](https://github.com/user-attachments/assets/68b625ec-df16-4702-b81c-8964e19ab462)

* Переименовываем контейнер

![Снимок экрана 2025-01-23 в 17 09 20](https://github.com/user-attachments/assets/55d11083-146e-45e4-975b-04987bdc14bf)

* Несколько команд

![Снимок экрана 2025-01-23 в 17 10 41](https://github.com/user-attachments/assets/f215b3ab-7fe5-43db-9a8f-414e04ca925c)
![Снимок экрана 2025-01-23 в 17 13 02](https://github.com/user-attachments/assets/833af348-a0b2-4885-b832-d7b066cabc94)

* Проверка на доступность

![Снимок экрана 2025-01-23 в 17 13 33](https://github.com/user-attachments/assets/e64d3f99-487b-4206-a312-fe5fa34479d9)
![Снимок экрана 2025-01-23 в 17 14 04](https://github.com/user-attachments/assets/7e07decd-ec96-4eb6-841f-722294b2b361)

#ЗАДАНИЕ3

* Подключаемся к контейнеру и командой Ctr-C завершаем главный процесс контейнера

![Снимок экрана 2025-01-23 в 17 20 41](https://github.com/user-attachments/assets/4b7a5cf2-8444-4e4a-bfd2-afd418ed1794)
![Снимок экрана 2025-01-23 в 17 21 02](https://github.com/user-attachments/assets/d45f8614-c93d-45ff-87fb-33ebf6550f79)

* Обратно запускаем контейнер ставим Nano и редактируем "/etc/nginx/conf.d/default.conf", заменив порт с "listen 80" на "listen 81"

![Снимок экрана 2025-01-23 в 17 28 39](https://github.com/user-attachments/assets/db9e0fae-a1af-402f-8332-127ca0fa032a)
![Снимок экрана 2025-01-23 в 17 31 32](https://github.com/user-attachments/assets/a46cb189-828e-4b97-8925-39eeb5a4a3ba)
![Снимок экрана 2025-01-23 в 17 32 25](https://github.com/user-attachments/assets/f9bc0304-d371-4144-bba7-44e953207b10)

* Перезапускаем контейнер и видем, что ничего не видем

![Снимок экрана 2025-01-23 в 17 33 17](https://github.com/user-attachments/assets/258cd222-0fe8-494b-bf88-cc369b7bba43)
![Снимок экрана 2025-01-23 в 17 35 35](https://github.com/user-attachments/assets/948383e6-59f1-4f37-9556-5716ddc08b69)
![Снимок экрана 2025-01-23 в 17 33 34](https://github.com/user-attachments/assets/53dae5c2-a723-4e24-a59a-601b97003b55)

* И удоляем его без остановки

![Снимок экрана 2025-01-23 в 17 36 01](https://github.com/user-attachments/assets/34685d1b-59b2-46b4-8f10-1d45056f67a2)

#ЗАДАНИЕ4

* Запускаем контейнер Centos с интерактивной сейсию (просто у меня почему-то он не хотел работать если я запускал его обычной командой)

![Снимок экрана 2025-01-23 в 17 47 55](https://github.com/user-attachments/assets/1db7a009-5406-4078-86d4-0ba7a8331ad8)

* Создаем файл. И повторяем тоже самое для контейнера Debian.

![Снимок экрана 2025-01-23 в 17 53 20](https://github.com/user-attachments/assets/a3bb450b-a192-4d80-9032-3a3b5b971761)
![Снимок экрана 2025-01-23 в 17 55 22](https://github.com/user-attachments/assets/7cd51f5d-5c0e-4413-9d9a-5b70f910ab62)

* Подключитесь к первому контейнеру и создайте текстовый файл любого содержания Добавьте ещё один файл в текущий каталог на хостовой машине

![Снимок экрана 2025-01-23 в 17 56 06](https://github.com/user-attachments/assets/9dfa45b2-17c8-462e-9151-7505be487ab5)

#ЗАДАНИЕ5

* Создаем отдельную директорию и в ней два файла Compose.yaml и Docker-compose.yaml. Первый файл заполняем так чтобы сразу запускался и второй.

![Снимок экрана 2025-01-23 в 17 58 20](https://github.com/user-attachments/assets/70e62c74-bea8-41ce-9c26-a0463c7bc100)
![Снимок экрана 2025-01-23 в 18 01 09](https://github.com/user-attachments/assets/6d2bd319-7808-471b-b4a3-666026cedbfa)
![Снимок экрана 2025-01-23 в 18 03 01](https://github.com/user-attachments/assets/a3e8cae1-4268-4c1f-b96e-79ebc695d87d)
![Снимок экрана 2025-01-23 в 22 35 07](https://github.com/user-attachments/assets/b9963b45-058a-4d4a-927c-74c2ede298d3)

* Запускаем и пушим

![Снимок экрана 2025-01-23 в 18 05 00](https://github.com/user-attachments/assets/60f80eaa-bcd7-48be-8cd8-baf63aec4d55)
![Снимок экрана 2025-01-23 в 18 14 43](https://github.com/user-attachments/assets/d4f45782-5486-4875-9fd0-f11c60d38a4f)


* А вот и он

![Снимок экрана 2025-01-23 в 18 23 08](https://github.com/user-attachments/assets/92e40479-9a8e-40c2-ad69-61625474ae34)
![Снимок экрана 2025-01-23 в 18 26 20](https://github.com/user-attachments/assets/91fb183c-067c-437d-82f4-ff9a8fdc283d)
![Снимок экрана 2025-01-23 в 18 29 17](https://github.com/user-attachments/assets/1ce2ad5b-63d1-4f93-8768-c2b19cd2a39c)

* А теперь вызываем ошибку, удалив Compose файл, запущеного, контейнера. А после перезагружаем его.


![image](https://github.com/user-attachments/assets/d4caf2de-cfa7-45b9-8d51-3c35715ef65f)
![Снимок экрана 2025-01-23 в 18 38 30](https://github.com/user-attachments/assets/ed88aec1-a6ce-4813-9700-aba879866bc0)
