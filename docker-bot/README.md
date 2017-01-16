#Бот для чата [Радио-Т](https://chat.radio-t.com)

##Описание
Если в чате кто-то жалуется на то, что ведущие слишком долго обсуждают одну из своих излюбленных тем, этот бот сообщит, сколько раз та или иная тема была упомянута в чате в ходе текущего выпуска.
Изначально этот бот проектировался для подсчёта упоминаний слова "докер", но в последствии был доработан для того, чтобы понимать также и упоминание другой популярной темы для обсуждений.

## Примеры
Сообщение:
```json
{
  text: "Сколько можно про докер?",
  username: "test",
  display_name: "test"
}
```

Ответ:
```json
{
  bot: "docker-bot",
  text: "За текущий выпуск(№518) докер упоминали уже 1000 раз."
}
```

Сообщение:
```json
{
  text: "Сколько можно про apple?",
  username: "test",
  display_name: "test"
}
```

Ответ:
```json
{
  bot: "docker-bot",
  text: "За текущий выпуск(№518) apple упоминали уже 5000000 раз."
}
```