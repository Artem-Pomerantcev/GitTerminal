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
 
 . Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

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

. Отправить изменения на внешний репозиторий.

`git add Artem.xml`

`git commit -m "text Artem.xml"`

`git push`
 
 . Создать файл preferences.xml
 
 `touch preferences.xml`
 
 . В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 
 ```xml
 <?xml version="1.0" encoding="windows-1250"?>
   <book category="WEB">
      <title lang="en">Learning XML</title>
      <fav_movie>Terminal</fav_movie>
      <fav_series>Game of Thrones</fav_series>
      <fav_food>Pizza</fav_food>
      <fav_season>Summer</fav_season>
      <country>Spain</country>
   </book>
```

 . Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 
 `touch skills.xml`
 
```xml
<?xml version="1.0" encoding="windows-1250"?>
   <book category="WEB">
      <title lang="en">Learning XML</title>
      <terminal>Terminal</terminal>
      <git_hub>Git Hub</git_hub>
      <postman>Postman</postman>
     <sql>SQL</sql>
   </book>
```

 . Сделать коммит в одну строку.
 
 `git add . && git commit -m "add preferences.xml skills.xml"`
 
 
 . Отправить сразу 2 файла на внешний репозиторий.
 
 `git push`
 
 . На веб интерфейсе создать файл bug_report.xml.
 
 . Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 . На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 
 ```xml
 `<?xml version="1.0"?>
   <bug_reports>
       <email verbose="true" user_submission="true" />
       <json user_submission="false" directory="/tmp/reports/" />
       <sentry user_submission="false"/>
   </bug_reports>
```
 
 . Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 . Синхронизировать внешний и локальный репозиторий XML
 
 `git pull`
