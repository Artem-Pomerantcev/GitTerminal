 1.  Создать внешний репозиторий c названием XML.
 
 2. Клонировать репозиторий XML на локальный компьютер.
 
 `git clone ссылка`
 
 3. Внутри локального XML создать файл “new.xml”.
 
 `touch "Artem.xml"`
 
 4. Добавить файл под гит.
 
 `git add Artem.xml`
 
 5. Закоммитить файл.
 
 `git commit -m "add Artem.json"`
 
 6. Отправить файл на внешний GitHub репозиторий.
 
 `git push`
 
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

```xml

<?xml version="1.0" encoding="windows-1250"?>
   <book category="WEB">
      <title lang="en">Learning XML</title>
      <name>Artem</name>
      <age>22</age>
      <pets>1</pets>
      <salary>1000$</salary>
   </book>

```

8. Отправить изменения на внешний репозиторий.

`git add Artem.xml`

`git commit -m "text Artem.xml"`

`git push`
 
 . Создать файл preferences.xml
 
 `touch preferences.xml`
 
 9. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 
 ```xml
 <?xml version="1.0" encoding="windows-1250"?>
   <book category="WEB">
      <title lang="en">Learning XML</title>
      <fav_movie>"Termina"l</fav_movie>
      <fav_series>"Viking"</fav_series>
      <fav_food>"Pizza"</fav_food>
      <fav_season>"Summer"</fav_season>
      <country>"Spain"</country>
   </book>
```

 10. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 
 `touch skills.xml`
 
```xml
<?xml version="1.0" encoding="windows-1250"?>
   <book category="WEB">
      <title lang="en">Learning XML</title>
      <terminal>"Terminal"</terminal>
      <git_hub>"Git Hub"</git_hub>
      <postman>"Postman"</postman>
     <sql>"SQL"</sql>
   </book>
```

 11. Сделать коммит в одну строку.
 
 `git add . && git commit -m "add preferences.xml skills.xml"`
 
 
 12. Отправить сразу 2 файла на внешний репозиторий.
 
 `git push`
 
 13. На веб интерфейсе создать файл bug_report.xml.
 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 
 ```xml
 `<?xml version="1.0"?>
   <bug_reports>
       <email verbose="true" user_submission="true" />
       <json user_submission="false" directory="/tmp/reports/" />
       <sentry user_submission="false"/>
   </bug_reports>
```
 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 17. Синхронизировать внешний и локальный репозиторий XML
 
 `git pull`
