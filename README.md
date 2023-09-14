
<h1 align="center"># usePostman</h1>
<h2 align="center">Some API requests using Postman</h2>

<h3>Регистрация (Registration): </h3>

Новый запрос  >  метод POST  >  URL  :  https://blog.kata.academy/api/users  >  заголовок  :  Content-Type: application/json  >  тело запроса  :  данные пользователя в формате JSON




<h3>Логин (Authentication): </h3>

Новый запрос  >  метод POST  >  URL  :  https://blog.kata.academy/api/users/login  >  заголовок  :  Content-Type: application/json  >  тело запроса  :  данные для входа в формате JSON




<h3>Получение данных текущего пользователя (Get Current User): </h3>

Новый запрос  >  метод GET  >  URL  :  https://blog.kata.academy/api/user  >  заголовок  :  Authorization: Token xxxxxx.yyyyyyy.zzzzzz (получен при ^ аутентификации ^ )


