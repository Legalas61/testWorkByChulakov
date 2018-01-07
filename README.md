# test task By Chulakov
Test task from 1 December 2017
Задание #1:

Задание состоит из нескольких этапов, требующих различных навыков от исполнителя.

Этап #1:

Сверстать статическую страницу на основе макета с учетом нижеуказанных требований.

Браузеры: IE 10+, Chrome 40+, Firefox 40+, Safari 8+.

Стандарты: HTML5/CSS3.

HTML код: Структурный, комментируемый код (обозначается начало и конец крупных блоков). Семантичность. Грамотное использование тегов.

CSS код: Комментариями обозначены начало/конец наборов стилей.
Для оформления теней, скругленных углов и тд предпочтительно использовать CSS3-свойства.
Использование препроцессоров приветствуется.

JavaScript: Код должен выполняться без ошибок (проверить каждую страницу с помощью панели DevTools или аналогичной утилиты).
Код снабжен комментариями: описаны назначения функций и событий.

Нестандартные шрифты: Подключаются через директиву @font-face.

Концепция независимых блоков (БЭМ): Для сокращения риска коллизий в именах классов и повышения стабильности кода, в разработке рекомендуется (не обязательно) использовать концепцию независимых блоков (БЭМ).
Кратко о ней можно прочитать здесь: http://noteskeeper.ru/527/

Интерактивные элементы:
У всех интерактивных элементов должны быть проработаны необходимые состояния (например, наведение, фокус, клик).
На данном этапе можно не стилизовать выпадающие списки при помощи JS, а использовать стандартное оформление тэга <select>.

Этап #2:

Средствами CSS (@media-query) реализовать адаптивность в диапазоне ширины рабочей области от 320 до 1000 пикселей.

Должно быть проработано как минимум 4 состояния: 1000 (как на макете), 768, 480 и 320.

Макетов для уменьшенных состояний нет: внешний вид страницы при ширине меньше 1000px реализуется на усмотрение исполнителя тестового задания.

Этап #3:

Внедрить на страницу JS-валидацию и стилизовать выпадающие списки.

Условия валидации:
Все поля обязательны для заполнения;
Держатель карты только латинскими буквами, минимальная длина 4 символа;
Номер карты — в каждом поле 4 цифры;
CVV-код — только 3 цифры.

Некорректно заполненные поля обводятся красной рамкой.

Форма не отправляется пока не будет корректно заполнена.


Задание #2:

Дополнительная задача для кандидатов, претендующих на должность выше уровня Junior.

Реализовать простой графический редактор, работающий по следующему принципу:
При нажатии на холст, в месте клика появляется точка, которая соединена линиями с двумя предыдущими точками.

Демонстрация:
https://drive.google.com/open?id=0B8Wp21rbPmITZlRxQzgxbzNENWc

Технология реализации на усмотрение исполнителя.

Новая точка и линии, которые идут к двум предыдущим точкам имеют одинаковый цвет.

В случае, если точек еще нет, на холсте появляется только точка.
Если предудущая точка только одна, то линия всего одна — к этой точке.

Дополнительные бонусные задачи:

Анимированное появление точек;
Анимированная отрисовка линий;
Интерфейс для выбора цвета (например, color-picker или выбор из 5  разных цветов);
Возможность выбора числа точек с которыми будет происходить соединение (возможность задать другое значение отличное от 2).
