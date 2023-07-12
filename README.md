# postmanKata

Запрос на создание
POST https://blog.kata.academy/api/users

Тело запроса:

{
"user": {
"username": "Krioplas",
"email": "string@mail.ty",
"password": "strStr"
}
}

Ответ сервера:
{
"user": {
"username": "krioplas",
"email": "string@mail.ty",
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0YWQwMzM5NjBjNjc1MWIwMGI3OGYyNyIsInVzZXJuYW1lIjoia3Jpb3BsYXMiLCJleHAiOjE2OTQyNDQxNTMsImlhdCI6MTY4OTA2MDE1M30.Jul9x9fPfb2f5yU2mGOaIOVjAGA60p3ZXt44HXccFuY"
}
}

Запрос на авторизацию
POST https://blog.kata.academy/api/users

Тело запроса:

{
"user": {
"email": "string@mail.ty",
"password": "strStr"
}
}

Ответ сервера:
{
"user": {
"username": "krioplas",
"email": "string@mail.ty",
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0YWQwMzM5NjBjNjc1MWIwMGI3OGYyNyIsInVzZXJuYW1lIjoia3Jpb3BsYXMiLCJleHAiOjE2OTQzNTc0MDcsImlhdCI6MTY4OTE3MzQwN30.WZV2Bsp8NTaicYg_HJddd1NUgoc697_c-1PABto8zAo"
}
}

Запрос на данные пользователя
GET https://blog.kata.academy/api/user

Тело запроса:
Нет.

по Bearer Token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0YWQwMzM5NjBjNjc1MWIwMGI3OGYyNyIsInVzZXJuYW1lIjoia3Jpb3BsYXMiLCJleHAiOjE2OTQzNTc0MDcsImlhdCI6MTY4OTE3MzQwN30.WZV2Bsp8NTaicYg_HJddd1NUgoc697_c-1PABto8zAo

Ответ сервера:
{
"user": {
"username": "krioplas",
"email": "string@mail.ty",
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0YWQwMzM5NjBjNjc1MWIwMGI3OGYyNyIsInVzZXJuYW1lIjoia3Jpb3BsYXMiLCJleHAiOjE2OTQzNTc1ODYsImlhdCI6MTY4OTE3MzU4Nn0.Fw0FYhFvGA3oxnYSsCEAiJB1NyG52j8M5UYSTUvb1UU"
}
}
