# Функциональность сайта

Пользователь может работать с сайтом как в качестве «гостя», то есть не авторизованного пользователя, так и в качестве авторизованного пользователя.

В отличие от авторизованного пользователя, гость не может приступить к просмотру фильма, а может лишь получить какую-либо информацию об этом фильме (например, год производства или жанр). Поэтому в «шапке» сайта размещены две кнопки, при нажатии на которые произойдет переход на страницу авторизации (если пользователь уже регистрировался) или регистрации. Также преимущество авторизованного пользователя в том, что у каждого авторизованного пользователя существует список любимых фильмов. Некая корзина в которую пользователь может закинуть любой фильм который захочет досмотреть потом или же пересмотреть его через некоторое время снова.

Под «шапкой» сайта находится «слайдер», горизонтальная полоса с возможностью прокрутки в которой показаны новые фильмы на сайте.

«Слайдер» написан на JavaScript и CSS.

В основной части сайта находится поиск фильмов. Можно выбрать фильм из предложенного списка (список формируется на основе предпочтений данного пользователя при условии, что пользователь авторизован) или найти фильм (используя форму для поиска по названию или же используя фильтры).

После перехода на страницу с фильмом пользователь может ознакомиться с годом производства фильма, жанром, режиссёром, сценаристом, посмотреть трейлер или сам фильм.

**Библиотеки:**

1) Для работы с СУБД используется RedBeanPHP.