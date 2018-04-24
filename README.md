# Домашнее задание по React

Для запуска проекта выполни следующие шаги:

*   `git clone git@github.com:Lectrum/react-online-hometask.git`
*   `cd react-online-hometask`
*   `yarn` или `npm i`
*   `yarn start` или `npm start`

### Техническое задание

*   Суть задания: создать резюме, следуя предоставленному макету
*   Для старта можно использовать подготовленные компоненты и стили
*   Несколько компонентов содержат и разметку и стили, остальные — только стили. Если верстать не нравится/не хочется — можно использовать их как стартовую точку
*   При желании можно удалить компоненты и стили, и сделать все самостоятельно
*   При распечатке компонентов нужно максимально использовать переборы JavaScript — на пример `.map`, вручную дублировать компоненты в возвращаемом значении метода `render` — нельзя
*   Компоненты-списки содержат файлы формата `.json` с данными для рендера — их использование обязательно
*   В плане контента нужно заменить изначальные данные и фотографию своими, но при желании можно оставить изначальные
*   Закомментированного и не нужного кода в приложении быть не должно
*   А также, линтер должен быть чистым

#### Чтобы задеплоить приложение на github pages:

*   Запуши репозиторий с приложением на github
*   В файле `package.json`, в скрипте `build:prod-github` — укажи значение переменной окружения `REPOSITORY_NAME` в виде имени своего репозитория на github
*   Затем — `yarn deploy` или `npm run deploy`

###### Заметка: после деплоя, приложение будет доступно по адресу:

> `https://имя-твоего-пользователя-гитхаб.github.io/имя-твоего-репозитория-с-приложением`

#### Чтобы сбилдить приложение без github pages:

*   `yarn build:prod` или `npm run build:prod`
