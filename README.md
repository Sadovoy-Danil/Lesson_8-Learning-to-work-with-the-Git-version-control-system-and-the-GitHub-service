# Lesson_8-Learning-to-work-with-the-Git-version-control-system-and-the-GitHub-service

_**Git**_ очень удобный инструмент программиста, с его помощью мы можем делать "контрольные точки" в нашем коде. Это можно назвать сохранением, но главное удобство в том, что в любой момент можно вернутся к любой его версии (ну если вы сохранились).

<hr>

> _**Git хороший заменитель Ctrl + C ;)**_

<hr>

Для того чтобы воспользоватся возможностями Git'а нам прийдется его [скачать](https://git-scm.com/). _**Как пользоватся Git'ом?**_

1) Зайти в терминал нужной вам папки (Shift + Ctrl + . / Visual Studio Code --> Terminal)

2) Прописать команду 'git init' + Enter, тем самым объясняя Git'у, чтобы он следил за данной папкой

3) Для начала требуется представится:
 
 > - git config --local user.name "Your Name" + Enter
 
 > - git config --local user.email monstr14ekss@gmail.com + Enter
 
 4) Для того, чтобы узнать состаяние Git'а пропишите команду _git status_ + _Enter_
 
 5) Чтобы перевести файлы во II-ое состояние надо сказать Git'у — _'Следи за ними!'_ или _git add -A_
 
 6) Для того, чтобы локально сохранить контрольную точку в Git'е, напишите — _git commit -a -m"Your commit" (III-я фаза Git'а)_
 
 7) После этого нам предстоит отправить наши файлы на удаленный сервер:
 
 > - _регистрируемся на GitHub_
 
 > - _создаем новый репозиторий_
 
 > - _push'ым наши данные на репозиторий_
 
 Если все прошло успешно, мы увидем вот такую структуру -->
 
 
 <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img src = '/img/screenshot.jpg' align = 'center'> </p>
 
 
 > _**Если вы впервые работаете с Git'ом, то лучше 'представится' глобально на весь компьютер -->**_ <s><i><b>local</i></b></s> <u><i><b>global</i></b></u>
 
<hr>

<h3 align = 'center'><a href = 'https://githowto.com/ru'><i>Git How To</i></a></h3>

<hr>

_**Словарь**_

[_Git_](https://ru.wikipedia.org/wiki/Git) —  распределённая **система управления версиями**. <img src = '/img/Git_Logo.png' align = 'right'>

[_Cистема управления версиями_](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F%D0%BC%D0%B8) — **программное обеспечение** для облегчения работы с изменяющейся информацией.

[_Программное обеспечение (ПО)_]() — программа или множество программ, используемых для управления компьютером.

[_GitHub_](https://ru.wikipedia.org/wiki/GitHub) — крупнейший [веб-сервис](https://ru.wikipedia.org/wiki/%D0%92%D0%B5%D0%B1-%D1%81%D0%BB%D1%83%D0%B6%D0%B1%D0%B0) для [хостинга](https://ru.wikipedia.org/wiki/%D0%A5%D0%BE%D1%81%D1%82%D0%B8%D0%BD%D0%B3) [IT-проектов](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D0%B5_%D1%82%D0%B5%D1%85%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D0%B8) и их совместной разработки.

