## Привет!
Это тестовое задание для кандидатов на должность фронтенд-разработчика в 2ГИС. Свои результаты нужно выложить на GitHub и прислать ссылку человеку, который с тобой контактировал.

## Задание №1
В контейнере есть 4 элемента одинаковой фиксированной ширины. Нужно равномерно распределить их по контейнеру следующим образом:

![](/bars4.png?raw=true)

##### Условия
- Контейнер резиновый;
- Четвёртый элемент всегда прижат к правому краю;
- Если элементов меньше чем 4, то они всё равно должны занимать такие же позиции, будто их 4.

Так должен выглядеть контейнер с тремя элементами:

![](/bars3.png?raw=true)

Не так:

![](/bars_incorrect.png?raw=true)

Вёрстка должна корректно отображаться в последних версиях популярных браузеров (Chrome, Firefox, Safari, Opera, IE).

Постарайся выполнить задачу разными способами и опиши преимущества/недостатки каждого из них.

## Задание №2
Необходимо реализовать функцию на JavaScript, которая будет тестировать вёрстку из задания №1.

Вызов функции происходит после полной загрузки страницы.

За один проход функция должна проверить корректность условий для 4 состояний вёрстки: когда внутри контейнера 1, 2, 3 или 4 элемента.

Условия для тестирования (можешь дополнить список своими вариантами):
- Контейнер существует и его ширина равна ширине родителя;
- Количество элементов внутри контейнера не менее одного и не более четырёх;
- Элементы имеют одинаковые размеры;
- Расстояние между элементами всегда одинаковое, даже при изменении количества элементов.

Визуализируй результаты тестирования любым удобным способом.
