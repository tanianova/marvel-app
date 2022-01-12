### Marvel app

##### React приложение с использованием Marvel API, в котором можно подробно изучить героев и комиксы из вселенной Marvel

Проект развернут на https://marvel-testing1.herokuapp.com/

Реализация:
* работа с API(запросы, получение данных с сервера)
* загрузка рандомного персонажа с сервера (валидация описания персонажа)
* условный рендеринг, спиннер, обработка ошибок (при запросе к серверу)
* жизненный цикл компонентов, предохранители
* вывод списка персонажей и их полное описание(поднятие состояния)
* пагинация данных(дозагрузка персонажей)
* проверка типов с помощью prop types
* использование ref для фокусировки на выбранном персонаже
* развертывание проекта на heroku
* перевод классовых компонентов на функциональные (использование хуков useState,useEffect,useRef)
* создание собственных хуков( вынос повторений по загрузке данных с сервера)
* добавление страницы с комиксами(загрузка данных с API)
* маршрутизация с использованием React Router v5: BrowserRouter, Route, Switch, Link, NavLink
* обновление React Router на v6: Routes, element
* добавлена страница 404 для несуществующих страниц
* динамические пути и детальная страница для каждого комикса
* динамически импорты, React.lazy, React.Suspense  для оптимизации загрузки страниц
* использование библиотеки React Transition для плавной подгрузки элементов на главной странице 
* форма для поиска каждого персонажа с использованием библиотеки Formik
* react helmet (title, meta-тэги)
* принцип конечного автомата (finite-state machine)