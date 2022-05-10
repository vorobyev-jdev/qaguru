# QaGuru demo App

##Небольшой веб-сервис, позволяющий хранить информацию о пользователях с доступом по REST.  
Логика работы:
###@GetMapping(value = "qaGuru/userinfo?userId=X")
Возаращает информацию о пользователе X

###@GetMapping(value = "qaGuru/reset")
Сбрасывает состояние сервиса

###@GetMapping(value = "qaGuru/info")
Возаращает количество созданных пользователей


###@PostMapping(value = "qaGuru/createuser")
{
"id": 2,
"name": "vasya2"
}
Создаёт пользователя с полями указанными в json

Эндпоинты свагера -  
  http://yourHost:8080/swagger-ui.html  
  http://yourHost:8080/v2/api-docs  
