JSON
 1. Создать внешний репозиторий c названием JSON.

amithehost_JSON

 2. Клонировать репозиторий JSON на локальный компьютер.
 
git clone https://github.com/Amithehost/amithehost_JSON.git

 3. Внутри локального JSON создать файл “new.json”.

touch new.json

 3. Добавить файл под гит.

git add new.json	

 4. Закоммитить файл.

git commit -m "add first file"

 5. Отправить файл на внешний GitHub репозиторий.
 
 git push
 
 6 Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

cat >> new.json

{	

"Full name": "Глот Ксения Васильевна",
"Age": 27,
"Number of pets": 1,
"Future desired slary": 1000

}

CTRL+D

7 Отправить изменения на внешний репозиторий.

git add . ; git commit -m "changes json file" ; git push	

8.Создать файл preferences.json

touch preferences.json

9.В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

cat >> preferences.json

{

"Favoutite movie": "Black Knight",
"Favourite TV show": "Big Bang Theory",
"Favourite food": "Cakes",
"Fouvorite time of year": "Summer",
"Country you would like to visit": "Ireland"

} 

CTRL+D

10. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

cat >> skills.json

{

"Skills": "Linux, Bash, Git, GitHub, API, HTTP/HTTPS, Web Testing, Mobile Testing, Proxy, VPN, SQL, JMeter"

}

CTRL+D

11. Отправить сразу 2 файла на внешний репозиторий.

git add . ; git commit -m "add two files" ; git push

12. На веб интерфейсе создать файл bug_report.json.

Создали файл bug_report.json в GitHub в веб-интерфейсе

 13. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
Сделали коммит в веб-интерфейсе GitHub

 14. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 
В веб-интерфейсе GitHub отредактриовали (модифицировали) файл bug_report.json

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
Сделали коммит в веб-интерфейсе GitHub

 16. Синхронизировать внешний и локальный репозиторий JSON
 
git fetch

git pull
