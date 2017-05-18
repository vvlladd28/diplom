Запуск
1. docker-compose.yml - установка nextcloud
2. Зайти localhost і створити акаунт і ввести парамети db
3. Перейти в /nextcloud/apps/ і виконати команду git clone https://github.com/ONLYOFFICE/onlyoffice-owncloud.git onlyoffice
4. На сайті перейти на вкладу apps (біля емблеми лівий верхній угол Files) і на вкладці Not enabled вибрати onlyoffice
5. Я запускав офіс через команду docker run -i -t -d -p 8080:80 -v /mnt/docker/onlyoffice/logs:/var/log/onlyoffice onlyoffice/documentserver, хоча я знайшов файл docker-compose.office.yml в мене не вдалося запустити офіс через нього.
6. На владці сховища admin (випадаюче меню на імені корістувача, шапка крайній правий угол), внизу сторінки прописати для пункту onlyoffice його домен. 
 
