# XSS-attack
## Реализация задания по курсу Web и DHTML -- XSS атака

В нашем случае сервер, который будет атаковать -- на порту 4200, а атакуемый -- 3000

Последовательность действий:
Мы представляем сторону зла и заходим по адресу localhost:3000/opinion, где в поле "Ваше мнение" вводим атакующий скрипт и отправляем форму
После этого мы представляем сторону добра и как ничего не подозревающий пользователь так же заполняем форму
Происходит переадресация и мы видим данные, введенные ранее и мнения других пользователей, среди которых атакующий скрипт
Пау! Атакующий скрипт выполняется и куки уплывают
