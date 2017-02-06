Index
1. Классы у одинаковых кнопок на разных страницах .btn--orange и .btn--bg-orange
2. В разметке нет блока "Здоровый отдых"
3. Разметку галереи нужно будет дописать (пример галереи будет на занятии по jquery)
4. <div class="reviews__header">, <div class="reviews__footer"> - вероятно лишние
5. rewiews - написано с ошибкой
6. <div class="rewiews__body"> - это контейнер одного отзыва или всей галереи? В любом случае их должно быть два.
7. в отзыве 'vk' - это ссылка
8. <button class="rewiews__btn"> - по идее это тоже кнопка (с классом .btn)
9. <div class="slider"> - опять же должен быть отдельно контейнер для слайдера и отдельно контейнер для слайда. Назвать лучше типа .discount__slider
9а. В слайдере изображение контентное, а тэга img нет.
10. Скорее всего для блоков .contacts__info будет нужен объединяющий контейнер.
11. А вот в блоке .contacts__info изображение как раз оформительское, img не надо, можно поставить его в псевдоэлемент.
12. <span class="contacts__name"> - не span, блочный элемент
13. <section class="cottage-hotel"> - название блока не семантично, лучше что-то типа .rest-choise
14. .item-sale-box - то же самое
15. <p>Текст цены <span="item-sale-box__price">12354</span>сутки</p> - это БЛОК. Т.к. встречается на других страницах
16. В футере видимо остальные иконки и строки потом добавишь, пока там не все.

Rooms
1. В блоке .rooms-information-main объединить .rooms-information-main__text и две кнопки в общий блок (будет нужно для расстановки флексами)
2. Вероятно две кнопки тоже нужно объединит в общий блок
3. Порядок следования блоков в разметке верный.

Single-room
1. <section class="single-room"> - нет классов у h2 и span под ним (это блок, такой же как и тот что на index) и их оба я бы объединил в один блок
2. <div class="single-room__img"> и <div class="single-room__info"> - объединить в один блок
3. Две кнопки объединить в общий блок
4. Внутри <div class="diff-rooms__item-picture"> - должен быть img
5. Этот блок переписать!
<div class="rooms-info">
    <span class="rooms-info__subtitle">В отеле</span>
    <span class="rooms-info__price">от <span class="rooms-info__price--orange   rooms-info__price--text-larger">4000</span> руб./сутки</span>
</div>
