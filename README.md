# Инструкции как сделать "pull request" чужого репозитория
1) Переходим на страницу интересуемого нами репозитория
2) Находим кнопку с вилкой
3) Создаем вилку - мы молодцы!
<img src="https://github.com/Aeverandi/pull_request_instructuins/blob/main/imgs/01.png" />

4) Возвращаемся в свой аккаунт
5) Выбираем свои реппозитории
6) Чудесным образом находим копию интересовавшего нас репо у себя
<img src="https://github.com/Aeverandi/pull_request_instructuins/blob/main/imgs/02.png" />

7) Создаем локально папку/проект и открываем в нем терминал. Далее будут команды для терминала:
8) `git init` - запускаем git
9) `git clone https://github.com/Aeverandi/seminar_ci_cd.git` - клонируем локально
10) `git checkout -b имя-новой-ветки` - создаем ветку
11) `cd seminar_ci_cd` - переходим в папку клонированного репо
12) `git add .` - добавляем все папки к клону
13) Производим необходимые изменения в коде
14) `git commit -m "комментарий"` - коммитим
15) `git push origin имя-новой-ветки` - переносим изменения на github.com
16) Возвращемся по адресу своего реппозитория и находим вкладку "**Pull requests**"
<img src="https://github.com/Aeverandi/pull_request_instructuins/blob/main/imgs/03.png" />

17) Дальше создаем новый request, все вполне интуитивно
<img src="https://github.com/Aeverandi/pull_request_instructuins/blob/main/imgs/04.png" />

18) Ждем ответ автора первичного репозитория 
