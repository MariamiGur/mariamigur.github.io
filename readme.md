**Project forkio**

1)Наш макет мы сверстали в трех разрешениях - 320 пикселей, 768 пикселей, и 1200 пикселей.
Макет мы сделали с учетом принципов адаптивной и резиновой верстки (все блоки/колонки должны занимают всю доступную ширину экрана (с учетом боковых отступов - 10px там, где есть контент)).
Мы протестировали наш проект на экране шире чем 1200 пикселей, контент у нас занимает ровно 1200 пикселей,находиться по центру, верстка выглядит хорошо на разных девайсах и при разрешениях экрана.
В проекте мы добавили псевдокласс - hover для кнопок, меню (навигации) и лого для улучшения вижуала сайта.
Также для удобного открытия меню в мобильной версии мы сделали выпадающее меню с помощью чистого JS.
Кнопки - watch, start, fork сделаны ссылками для дальнейшего подключения JS.

Проект был собран с помощью сборщика Gulp, в корне проекта мы создали папку src, а также файл index.js.
Стили и скрипт index.html подключены из папки dist после запуска "npm run dev".
Содержимое папки dist генерируется автоматически путем преобразования и копирования файлов, которые находятся в нашей папке src.
У нас есть два основных рабочих задания для Gulp: dev и build.

Все классы на странице у нас заданы с использованием методологии BEM и все стили написаны в файлах SCSS.
При сборке проекта мы использовали npm пакеты, которые помогли нам улучшить сборку и эффективность создания и работы проекта:
gulp
del
gulp-sass
browser-sync
gulp-js-minify
gulp-uglify
gulp-clean-css
gulp-clean
gulp-concat
gulp-imagemin
gulp-autoprefixer.
​
2) Morshna Oleg, Mariami Gurgenidze
3) Mariami - TASK 1
Сверстала шапку сайта с верхним меню (включая выпадающее меню при малом разрешении экрана).
Сверстала секцию People Are Talking About Fork;
Oleg - TASK 2
Сверстал блок Revolutionary Editor.
Светстал секцию Here is what you get.
Сверстал секцию Fork Subscription Pricing.


