
<h1 align="center"># usePostman</h1>
<h2 align="center">Some API requests using Postman</h2>

<h3>Регистрация (Registration): </h3>

Новый запрос  >  метод POST  >  URL  :  https://blog.kata.academy/api/users  >  заголовок  :  Content-Type: application/json  >  тело запроса  :  данные пользователя в формате JSON

![Registration request using Postman](https://github.com/GreyHound87/usePostman/blob/main/PMScr-1.jpg)


<h3>Логин (Authentication): </h3>

Новый запрос  >  метод POST  >  URL  :  https://blog.kata.academy/api/users/login  >  заголовок  :  Content-Type: application/json  >  тело запроса  :  данные для входа в формате JSON

![Authentication request using Postman](https://github.com/GreyHound87/usePostman/blob/main/PMScr-2.jpg)


<h3>Получение данных текущего пользователя (Get Current User): </h3>

Новый запрос  >  метод GET  >  URL  :  https://blog.kata.academy/api/user  >  заголовок  :  Authorization: Token xxxxxx.yyyyyyy.zzzzzz (получен при ^ аутентификации ^ )

![Get Current User request using Postman](https://github.com/GreyHound87/usePostman/blob/main/PMScr-3.jpg)
