# POSTMan-Task

## Регистрация
### Отправленный запрос
```
{
  "user": {
    "username": "UNDECO9VER",
    "email": "arsen01998@yandex.ru",
    "password": "Somepassword1"
  }
}
```
### Полученный ответ
```
{
    "user": {
        "username": "undeco9ver",
        "email": "arsen01998@yandex.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNTU4MWRhM2NmNzA1MWIwMDgyYjQ4MCIsInVzZXJuYW1lIjoidW5kZWNvOXZlciIsImV4cCI6MTY3MTczMjE4NiwiaWF0IjoxNjY2NTQ4MTg2fQ.kt8_tMKFgTjPQHxqvTV2LCs2MpdXw3yKi81QeG6AeAs"
    }
}
```  
## Авторизация
### Отправленный запрос
```
{
  "user": {
    "email": "arsen01998@yandex.ru",
    "password": "Somepassword1"
  }
}
```
### Полученный ответ
```
{
    "user": {
        "username": "undeco9ver",
        "email": "arsen01998@yandex.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNTU4MWRhM2NmNzA1MWIwMDgyYjQ4MCIsInVzZXJuYW1lIjoidW5kZWNvOXZlciIsImV4cCI6MTY3MTczMjI0MywiaWF0IjoxNjY2NTQ4MjQzfQ.9Pl1Qnnj8EwP_pKfa5t5JSk2gb7VXtRgy3OcA2YLsw8"
    }
}
```
## Получение данных текущего пользователя
### Полученный ответ
```
{
    "user": {
        "username": "undeco9ver",
        "email": "arsen01998@yandex.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNTU4MWRhM2NmNzA1MWIwMDgyYjQ4MCIsInVzZXJuYW1lIjoidW5kZWNvOXZlciIsImV4cCI6MTY3MTczMjU1NywiaWF0IjoxNjY2NTQ4NTU3fQ._0jX3oe4xSNyQWnjhGHIXGnyRwKKqIJIFMHQFe4wz30"
    }
}
```
