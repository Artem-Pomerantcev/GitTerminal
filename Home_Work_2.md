### JSON
 1. Создать внешний репозиторий c названием JSON.
 
 2. Клонировать репозиторий JSON на локальный компьютер.
 
 `git clone "название ссылки"`
 
 3. Внутри локального JSON создать файл “new.json”.

`touch Artem.json`

 4. Добавить файл под гит.
 
 `git add Artem.json`
 
 5. Закомитить файл
 
 `git commit -m "add Artem.json"`
 
 6. Оавить файл на внешний GitHub репозиторий.
 
 `git push`
 
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 
 `nano Artem.json`
 
 ```java
 {
    "Name" : "Atem"
    "LastName" : "Pomerantcev"
    "MiddleName" : "Igorevish"
    "Age" : 22,
    "Pets" : 1
    "Salary" : "500$"
 }
 ```
 
 8. Отправить изменения на внешний репозиторий.
 
 `add Artem.json`
 `git commit -m "shange Artem.json`
 `git push`
 
 9. Создать файл preferences.json
 
 `touch preferences.json`
 
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 
 ```java
  {
    "Favorite film" : "Terminal"
    "Favorite Series" : "Viking"
    "Favorite Food" : "pizza"
    "Favorite Season" : "Summer",
    "Coutry which i want to visit" : "Spain"
 }
 ```
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 
 `touch skills.json`
 `nano skills.json`
 
 ```java
 {
    "1" : "Terminal",
    "2" : "Git",
    "3" : "Postman",
    "4" : "Python",
    "5" : "Fiddler",
    "6" : "Jmeter",
    "7" : "SQL"
 }
 ```
 12. Отправить сразу 2 файла на внешний репозиторий.
 
 `git add ..`
 `git commit -m "add 2_files"`
 `git push`
 
 13. На веб интерфейсе создать файл bug_report.json.
 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 15.На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

```java

     
    "Bug ID" : 123,
    "Area Path" : "user menu",
    "Build Number" : "Version Number 5.0.1",
    "Severity" : "High",
    "Priority" : "Medium",
    "Assigned to" : "Developer-X",
    "Reported By" : "artem"
    "Reported On" : "23.02.2022"
    "Reason" : "Defect",
    "Status" : "Open",
    
 }
 ```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 17. Синхронизировать внешний и локальный репозиторий JSON
 
 `git pull`
