# <h3>Шаблон для быстрого старта проекта</h3><br>

<h3>Что вошло в сборку:</h3>
1 SASS - препроцессор;<br>
2 Gulp - сборщик проектов;<br>
    Плагины, которые вошли в сборку:<br>
    <ul style="list-style-type: none;">
        <li>gulp-autoprefixer</li>
        <li>gulp-concat-css</li>
        <li>gulp-livereload</li>
        <li>gulp-connect</li>
        <li>gulp-minify-css</li>
        <li>gulp-notify</li>
        <li>gulp-rename</li>
        <li>gulp-sass</li>
        <li>gulp-uglify</li>
    </ul>
    
3 Typography and grid:<br>
    <ul style="list-style-type: none;">
        <li>Libsass Compass Vertical Rhythm - typography</li>
        <li>Susy Grid - "умная" сетка</li>
    </ul>

4 Material SVG icons<br>
    Инфо по способу подключения
    ~~~
    https://github.com/google/material-design-icons/tree/master/sprites
    ~~~
    Пример подлючения в html:
    ~~~
    <svg class="svg-24px">
        <use xlink:href="libs/material-design-icons/svg-sprite/svg-sprite-action-symbol.svg#ic_accessibility_24px"></use>
        <use class="check" xlink:href="MaterialIcons.svg#ic_check_box"></use>
    </svg>
    ~~~
    в данном примере:
    - svg-sprite-action-symbol.svg - svg файл из папки libs/material-design-icons/svg-sprite/
    - #ic_accessibility_24px - id выбраной иконки.

<h3>Старт проекта:</h3>

1. Копируем репозиторий.
	~~~	
	git clone https://github.com/MikhalevValentin/quick-start-template.git
	~~~

2. Устанавливаем Gulp  и плагины  
	~~~
	npm install
	~~~

3. Запускаем gulp 
	~~~
	gulp
	~~~
4. Открываем в браузере 
    <pre>
    <code>http://localhost:3400</code>
    </pre>