# XML
21. Создать внешний репозиторий c названием XML.
Создаём на гитхабе репозиторий XML
 22. Клонировать репозиторий XML на локальный компьютер.
git clone git@github.com:AndreiBileichyk/XML.git
 23. Внутри локального XML создать файл “new.xml”.
touch new.xml
 24. Добавить файл под гит.
git add new.xml
 25. Закоммитить файл.
git commit -m "creat new.xml"
 26. Отправить файл на внешний GitHub репозиторий.
git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
cat>> new.xml

<?xml version="1.0" encoding="utf-8"?>
<the first catalog>
<name>Билейчик Андрей Валентинович</name>
<age>36</age>
<number of pets>1</number of pets>
<future desired salary>500</future desired salary>
</the first catalog>

cntr+c

 28. Отправить изменения на внешний репозиторий.
git add new.xml
git commit -m "up new.xml"
git push
 29. Создать файл preferences.xml
touch preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
cat>> preferences.xml
<?xml version="1.0" encoding="utf-8"?>
<the second catalog>
<favorite movie>Легенда №17</favorite movie>
<favorite show>Молодежка</favorite show>
<favourite food>пицца</favourite food>
<favorite time of year>зима</favorite time of year>
<party you wish to visit>Сингапур</party you wish to visit>
</the second catalog>
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
cat>> sklls.xml 
<?xml version="1.0" encoding="utf-8"?>
<the third catalog>
<skills1>Git</skills1>
<skills2>github</skills2>
<skills3>git bash</skills3>
<skills4>Jmeter</skills4>
<skills5>mobile and web testing</skills5>
<skills6>API</skills6>
<skills7>sql</skills7>
<skills8>data transfer protocols</skills8>
</the third catalog>
cntr+c
 32. Сделать коммит в одну строку.
git add . ; git commit -m "add two file"
 33. Отправить сразу 2 файла на внешний репозиторий.
git push
 34. На веб интерфейсе создать файл bug_report.xml.
создать на гитхабе файл
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
зайти в файл bug_report.xml 
редактировать
в Commit changes написать up file
нажать Commit changes
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
зайти в файл
редактировать:
<?xml version="1.0" encoding="utf-8"?>
<the fourth catalog>
<Summary>Что? Где? При каких условиях?</Summary>
<Description>STR, result, expected result</Description>
<Priority>Low</Priority>
<nvironment>windows 10, google chrom ver..</nvironment>
<Attachment>scrin</Attachment>
</the fourth catalog>
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
git fetch
 38. Синхронизировать внешний и локальный репозиторий XML
git pull
