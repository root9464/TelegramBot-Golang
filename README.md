# TelegramBot-Golang
Многофункциональный телеграмм бот написанный на go

## Задачи:
  1) Написасать функционального бота на golang и оптимизировать его работу 
  2) Реализовать намеченный или приблизительно похожий функционал
  3) Подключить его к бд по возможности

## Функционал:

  ### Сложная версия:
  1) Пересылка сообщений : пользователь с правами admin отправляет сообщение боту после чего он пересылает        введеное сообщение в выбранную  admin'ом группу к которой подключен бот
  2) Бот парсит официальный сайт колледжа и берет данные о расписании групп после автоматический пересылает их в маркерованную группу или *2.1; 2.2;*

     > 2.1) Колледж имеет базу данных в которой есть актуальное расписание всех групп, после автоматический пересылает расписание в форматированном формате в маркерованную группу.
     
     >2.2) Бот имеет NoSql базу данных в которую заносятся данные о расписании всех групп, после автоматический пересылает расписание в форматированном формате в маркерованную группу
     
4) Бот имеет расширяемый функционал и оптимизируемую работу с данными
### Легкая версия:    
1) Пересылка сообщений : пользователь с правами admin отправляет сообщение боту после чего он пересылает введеное сообщение в выбранную  admin'ом группу к которой подключен бот
2) Бот парсит официальный сайт колледжа и берет данные о расписании групп после автоматический пересылает их к привязанной группе не имея многопоточного функционала и не распространяется на другие группы


| :exclamation:  Данная затея является лишь попыткой использования теоретических знаний. В случае неудачи автор не несет ответственности за неудачу, а лишь признается недостаточно опытным для задачи   |
|-----------------------------------------|
