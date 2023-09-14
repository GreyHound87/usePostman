
<h1 align="center"># usePostman</h1>
<h2 align="center">
some API requests using Postman</h2>

Регистрация (Registration): 

Новый запрос  >  метод POST  >  URL  :  https://blog.kata.academy/api/users  >  заголовок  :  Content-Type: application/json  >  тело запроса  :  данные пользователя в формате JSON




Логин (Authentication): 

Новый запрос  >  метод POST  >  URL  :  https://blog.kata.academy/api/users/login  >  заголовок  :  Content-Type: application/json  >  тело запроса  :  данные для входа в формате JSON




Получение данных текущего пользователя (Get Current User): 

Новый запрос  >  метод GET  >  URL  :  https://blog.kata.academy/api/user  >  заголовок  :  Authorization: Token xxxxxx.yyyyyyy.zzzzzz (получен при ^ аутентификации ^ )


