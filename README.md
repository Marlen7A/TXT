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
:Full name: Marlen Abliakimov
Age: 34
Pets: 1 dog
Desired Salary: 5000$

 ```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
 ### __8. Отправить изменения на внешний репозиторий.__
- *`git commit -am "new information add"`*
- *`git push`*
### __9. Создать файл preferences.txt.__
- *`touch preferences.txt`*
### __10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT.__
- *`vim preferences.txt`*
- *Insert*
 ```
Favorite movie: The Terminal
Favorite series: Suits
Favorite food: Pasta
Favorite season: Summer
Country I would like visit: Japan

```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
### __11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT.__
- *`cat > skills.txt`*
```
Skills:
1. Software testing theory
2. Linux terminal
3. GitBash
4. GitHub
5. DevTools
6. SQL
7. Postman
8. Jmeter
9. Fiddler
10. Python

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
ID: 123
Severity: Critical
Priority: High
Status: New
Title: Нажатие кнопки 'Контакты' на главной странице не перенаправляет на страницу Контакты.
Project: Интернет-магазин 'Колесо'.
Step 1. Зайти на главную страницу сайта.
Step 2. Нажать кнопку 'Контакты'.
OS: Windows 10 x64 build 19045.2965
Browser: Google Chrome v113.0.5672.93 x64 bit.
Component: Кнопка 'Контакты'.
Actual result: Нажатие кнопки 'Контакты' не перенаправляет на страницу Контакты.
Expected result: Нажатие кнопки 'Контакты' перенаправляет на страницу Контакты.
Attachments: Cсылка на картинку или видео с багом.
Author: Марлен Аблякимов

```
### __16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
-  *Нажать  __Commit changes.__*
### __17. Синхронизировать внешний и локальный репозиторий TXT.__
- *`git pull`*
