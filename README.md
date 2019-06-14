# Пример деплоя приложения на Node.js на сервера Heroku

Демонстрация этого приложения: https://example-node-deploy.herokuapp.com/

### Кратокое описание 
Мы можем настоить деплой приложения либо через веб-интерфейс [Heroku](https://heroku.com), либо через консольную утилиту [Herocu CLI](https://devcenter.heroku.com/articles/heroku-cli#download-and-install).
В `./Procfile` мы указываем, какую команду выполнить на сервере по окончанию деплоя. Это может быть `web: node server.js` либо `web: npm start`. Более подробное описание [Procfile](https://devcenter.heroku.com/articles/procfile).
Есть возможность как настроить автоматический деплой при внесении изменений например в ветку master, так и деплой по CLI команде/нажатию кнопки в веб интерфейсе.

