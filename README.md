# TXT
 ### __1. Создать внешний репозиторий с названием TXT.__ 
 - *Открыть* [GitHub](https://github.com/new "Создание нового репозитория")  
 - *В поле __Repository name__ ввести __TXT__*.
 - *В чекбоксе __Public__ выбрать*:
    - [x] __Public__
    - [ ] Private
 -  *Выбрать __Add a README file__.*
 -  *Нажать __Create repository__*.
  ### __2. Клонировать репозиторий TXT на локальный компьютер.__ 
 - *В репозитории __TXT__ нажать на  __Code__ затем в разделе __HTPPS__ скопировать ссылку.*
 - *В __Gitbash__ написать команду и вставить ссылку (для Windows, вставить Shift+Insert)*
 - *`git clone https://github.com/Marlen7A/TXT.git`*
### __3. Внутри локального TXT создать файл "new.txt".__ 
- *`touch new.txt`*
- *`git status` файл __new.txt__ отображается красным, изменения в файле не отслеживаются*.
### __4. Добавить файл под гит.__ 
- *`git add new.txt`*
### __5. Закомитить файл.__ 
- *`git commit -m "add new.txt"`*
### __6. Отправить файл на внешний GitHub репозиторий.__ 
- *`git push`*
### __7. Отредактировать содержание файла "new.txt"-написать информацию о себе (ФИО,возраст, количество домашних животных, будущая желаемая зарплата). Все написать в формате TXT.__ 
- *`vim new.txt`*
- *Insert*
 ```
<?xml version="1.0"?>
<person>
  <fullname>Marlen Abliakimov</fullname>
  <age>34</age>
  <pets>
  <dog>1</dog>
  </pets>
  <desiredSalary>5000$</desiredSalary>
</person>
 ```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
 ### __8. Отправить изменения на внешний репозиторий.__
- *`git commit -am "new information added"`*
- *`git push`*
### __9. Создать файл preferences.txt.__
- *`touch preferences.txt`*
### __10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT.__
- *`vim preferences.txt`*
- *Insert*
 ```
<?xml version="1.0"?>
<preferences>
  <favoriteMovie>The Terminal</favoriteMovie>
  <favoriteSeries>Suits</favoriteSeries>
  <favoriteFood>pasta</favoriteFood>
  <favoriteSeason>summer</favoriteSeason>
  <countryIWouldLikeToVisit>Japan</countryIWouldLikeToVisit>
</preferences>
```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
### __11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT.__
- *`cat > skills.txt`*
```
<?xml version="1.0"?>
<skills>
<skill>SoftwareTestingTheory</skill>
<skill>LinuxTerminal</skill>
<skill>GitBash</skill>
<skill>GitHun</skill>
<skill>DevTools</skill>
<skill>SQL</skill>
<skill>Postman</skill>
<skill>Jmeter</skill>
<skill>Fiddler</skill>
<skill>Python</skill>
</skills>
```
- *__Enter__*
- *__CTRL+C__*
### __12. Отправить сразу 2 файла на внешний репозиторий.__
- *`git add . && git commit -m "add preferences.txt and skills.txt" && git push`*
### __13. На веб интерфейсе создать файл bug_report.txt.__
- *В репозитории __TXT__ нажать __Add file__ и выбрать __Create new file.__*
-  *В поле __Name your file__ ввести __bug_report.txt.__*
### __14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
-  *Нажать  __Commit changes__*
-  *Подтвердить  __Commit changes__*
### __15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.__
- *Открыть файл __bug_report.txt__ нажать на кнопку __Edid this file__ *
 ```
<?xml version="1.0"?>
<bugReport>
<ID>123</ID>
<Severity>Critical</Severity>
<Priority>High</Priority>
<Status>New</Status>
<Title>Нажатие кнопки 'Контакты' на главной странице не перенаправляет на страницу Контакты</Title>
<Project>Интернет-магазин 'Колесо'</Project>
  <STR>
     <step>1. Зайти на главную страницу сайта (ссылка сайта)</step>
     <step>2. Нажать кнопку 'Контакты'</step>
  </STR>
    <Enviroment>
      <OS>Windows 10 x64 build 19045.2965</OS>
      <Browser>Google Chrome v113.0.5672.93 x64 bit</Browser>
    </Enviroment>
 <Component>Кнопка 'Контакты'</Component>
 <ActualResult>Нажатие кнопки 'Контакты' не перенаправляет на страницу Контакты</ActualResult>
 <ExpectedResult>Нажатие кнопки 'Контакты' перенаправляет на страницу Контакты</ExpectedResult>
 <Attachments>Cсылка на картинку или видео с багом</Attachments>
 <Author>Марлен Аблякимов</Author>
 </bugReport>
```
### __16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
-  *Нажать  __Commit changes.__*
### __17. Синхронизировать внешний и локальный репозиторий TXT.__
- *`git pull`*
