XML
 1. Создать внешний репозиторий c названием - XML Создаем внешний репозиторий на сайте с названием "XML"
 2. Клонировать репозиторий XML на локальный компьютер - git clone https://github.com/ViktorNikolaev88/XML.git
 3. Внутри локального XML создать файл “new.xml” - touch new.xml
 4. Добавить файл под гит. git add new.xml
 5. Закоммитить файл. git commit - m "new file"
 6. Отправить файл на внешний GitHub репозиторий - git push
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 cat >> new.xml
 <info>                                                                         
 <fullname>Николаев Виктор Михайлович </fullname>
 <age>34</age>
 <petsqauntity>2<petsquntity>
 <wantedsalary>500</wantedsalary>
 </info>
 8. Отправить изменения на внешний репозиторий. - git push
 9. Создать файл preferences.xml - touch preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
<?xml version="1.0" encoding="UTF-8" ?>
<root>
  <favourite_film>Terminator_2</favourite_film>
  <favourite_series>LOST</favourite_series>
  <favourite_food>potato</favourite_food>
  <favourite_season>winter</favourite_season>
  <wanted_country_to_visit>USA</wanted_country_to_visit>
</root>
 11. Создать файл skils.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
cat > sklls.xm
<?xml version="1.0" encoding="UTF-8" ?>
<root>
  <Skills>
    <first_skill>Testing</first_skill>
    <second_skill>Bug_report</second_skill>
    <third_skill>Regression_testing</third_skill>
    <fourth_skill>Black_box_testing</fourth_skill>
    <fifth_skill>Quality_control</fifth_skill>
    <six_skill>Exploratory_testing</six_skill>
  </Skills>
</root> 
 12. Сделать коммит в одну строку. - git add . - git commit -m "commit message"  
 13. Отправить сразу 2 файла на внешний репозиторий.- git push 
 14. На веб интерфейсе создать файл bug_report.xml.Кнопка Add file затем нажать Create new file
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. (нажать Commit changes)
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
<?xml version="1.0" encoding="UTF-8" ?>
<root>
  <Mobile_bug_13>
    <Environment>Iphone 12 mini Safari 16.2</Environment>
    <Title>При смене ориентации экрана с горизогнтальной на вертиальную и обртано едет верстка элемента [onetrust-banner-sdk]</Title>
    <Steps>1. Перейти на сайт https://capital.com 2. Сменить  положение утсройства с вертикального на гоаризонтальное</Steps>
    <Expected_result>При смене ориентации экрана с горизогнтальной на вертиальную и обртано  верстка элемента [onetrust-banner-sdk] подстравается под ориентацию экрана</Expected_result>
    <Actual_result>При смене ориентации экрана верстка элемента onetrust-banner-sdk едет, текст баннера заслоняет конпки</Actual_result>
  </Mobile_bug_13>
</root>
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. (нажать Commit changes)
 18. Синхронизировать внешний и локальный репозиторий XML git pull
