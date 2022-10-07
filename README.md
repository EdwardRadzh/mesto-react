# mesto-react

## Запуск проекта

`npm i` - установка зависимостей  
`npm run start` - запуск проекта  
`npm run build` - запуск сборки проекта  
`npm run dev` — запускает сервер с hot-reload

## Описание проекта
данный проект представляет собой интерактивное приложение. В этот сервис можно добавлять фотографии интересных мест, удалять их и ставить лайки.
Проект уже реализован на JS, сейчас он портирован на Реакт.

## Основной функционал
* отображение информации о пользователе и карточек на основе данных с сервера,
* возможность редактирования данных профиля и смены аватара пользователя,
* добавление новой карточки,
* постановка/снятие лайка,
* возможность удаления только карточек текущего пользователя,
* в форму редактирования профиля подставляются текущие данные.

## Инструменты и технологии
* HTML5
* CCS3
* JavaScript (ES6)
* React (Create React App, разметка портирована в JSX, функциональные компоненты и хуки)
* создан контекст текущего пользователя,
* выполнено поднятие стейта из компонент Main и Card,
* при работе с формами используются управляемые компоненты или ref,
* сайт адаптирован c media queries,
* flexbox,
* grid,
* БЭМ (наименование классов и организация файловой структуры),
* Webpack.
