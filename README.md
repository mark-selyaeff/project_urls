# Проект Перехожих Александры, группа М3111
## Создание короткой ссылки

Когда мы хотим поделиться какой-либо ссылкой с друзьями, часто сталкиваемся с проблемой, что эти ссылки очень длинные и не удобные для использования. Мой сервис преобразует преобразует длинную ссылку в короткую, что позволит удобнее прикреплять ее, например, в сообщении.

## Технологии
Использовано Django версии1.10.2, gunicorn, psycopg2

## Интерфейс
Главная странница. В строку необходимо ввести ссылку, которую вы хотите преобразовать. После нажать на кнопку "Создать"

![alt text](https://user-images.githubusercontent.com/22634614/26950221-f464d21e-4cad-11e7-9381-0136aa352a65.png)

Когда новая ссылка создана, просто нажмите на неё и Вы попадёте на нужную страницу, или скопируйте и отправьте ее другу.
![alt text](https://user-images.githubusercontent.com/22634614/26950354-65037304-4cae-11e7-9fb4-5089aab125e7.png)

![alt text](https://user-images.githubusercontent.com/22634614/26950558-0f7f1086-4caf-11e7-85f6-433a3a846663.png)

Если же ссылка уже была создана, то на экране выведется соответствующее сообщение, а счетчик посчитает сколько раз это было сделано.
![alt text](https://user-images.githubusercontent.com/22634614/26951230-75547138-4cb1-11e7-8913-71fa7055fae4.png)



