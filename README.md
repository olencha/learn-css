# learn-css

Позиционирование и анимация


1. Сверстать навигационное меню по шаблону:


![menu](/templates/menu-1.png)



Меню должно находиться вверху страницы и быть видимым даже при прокрутке страницы вниз (для демонстрации добавьте на страницу побольше содержимого, чтобы появилась вертикальная прокрутка).

На изображении приведены примеры меню, когда несколько кнопок/ссылок активны одновременно. В домашнем задании этого не требуется - сделайте, чтобы кнопка выглядела вдавленной только в момент нажатия (псевдокласс ":active"). По наведению курсора должна отображаться цветная полоска под кнопкой, а "вдавленности" быть не должно до нажатия кнопки.

Поместить результаты работы в файлы menu.html и menu.css.



2. Сверстать модальное окно по шаблону:



![modal](/templates/modal.png)



Окно должно отображаться посреди страницы и перекрывать все остальные элементы. Т.е. нужно сверстать не только саму форму ввода, но и чёрный полупрозрачный контейнер вокруг неё, заполняющий всё пространство страницы и не пропадающий при прокрутке (фиксированное позиционирование).

Поле ввода имеет голубую рамку (outline), когда на нём находится фокус. Кнопка тоже должна как-то меняться при наведении курсора и нажатии - на ваш вкус. Цветные полоски сверху делайте средствами CSS (для них не нужно никаких HTML-элементов - достаточно использовать линейный градиент с резким переходом цветов).

Поместить результаты работы в файлы modal.html и modal.css.



3. Сверстать меню, как на примере:



![menu-2](/templates/menu-2.gif)



Иконки можно взять любые другие: можно использовать glyphicons (если хотите сами разобраться), или подыскать стандартные Emoji в Unicode и вставить их напрямую, как символы. В крайнем случае, вместо иконок используйте обычные буквы A, B, C, ... Смысл в том, чтобы их цвет можно было менять по наведению курсора, так что использовать обычные png-изображения не получится.

Для фона можете найти любую другую подходящую картинку в интернете. Белые линии делайте с помощью CSS (это могут быть границы других элементов или псевдо-элементы ::before/::after с шириной или высотой в 1px и белым фоном, например).

Поместить результаты в файлы menu-2.html и menu-2.css.



4. Сверстать галерею с анимацией, как на этом примере:


![gallery](/templates/gallery.gif)


Возьмите какие угодно изображения для примера. Изначально все изображения стоят "стопкой": для этого используются 3-мерные трансформации в CSS (rotate) с использованием перспективы (см. google). При наведении курсора изображение плавно разворачивается и сдвигает остальные изображения.

Поместить результаты работы в файлы gallery.html и gallery.css.
