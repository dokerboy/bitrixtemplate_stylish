1С-Битрикс Bootstrap шаблон STYLISH
======================

HTML Шаблон (Bootstrap) интегрирован Задойным А.В. на 1С-Битрикс в рамках цикла уроков по интеграции Bootstrap вёрстки в 1С-Битрикс.

* [0 Урок](http://кофедизайн.рф/information/integratsiya_adaptivnogo_bootstrap_v_1C_bitrix_po_shagam_urok_0/) - Разметка
* [1 Урок](http://кофедизайн.рф/information/integratsiya_adaptivnogo_bootstrap_shablona_sayta_v_1C_Bitrix_po_shagam_urok_1/) - Первичная интеграция (статика)
* [2 Урок](http://кофедизайн.рф/information/integratsiya_adaptivnogo_bootstrap_shablona_sayta_v_1s_bitriks_po_shagam_urok_2/) - Включаемые области
* [3 Урок](http://кофедизайн.рф/information/integration_of_adaptive_bootstrap_site_template_in_1c_bitrix_steps_lesson_3/) - Слайдер
* [4 Урок](http://кофедизайн.рф/information/integration_of_adaptive_bootstrap_site_template_in_1C-Bitrix_steps_lesson_4/) - Форма поиска для шапки
* [5 Урок](http://кофедизайн.рф/information/integration_of_adaptive_bootstrap_site_template_in_1C-Bitrix_steps_lesson_5/) - Меню
* [6 Урок](http://кофедизайн.рф/information/integration_of_adaptive_bootstrap_site_template_in_1C-Bitrix_steps_lesson_6/) - Форма подписки (3 методами)
* [7 Урок](http://кофедизайн.рф/information/integration_adaptive_bootstrap_site_template_in_1c_bitrix_step_lesson_7/) - Тизерные блоки (на инфоблоках)
* [8 Урок](http://кофедизайн.рф/information/integration_adaptive_bootstrap_site_template_in_1c_bitrix_step_lesson_8/) - Список новостей на главной
* [9 Урок](http://кофедизайн.рф/information/integration_adaptive_bootstrap_site_template_in_1C-Bitrix_step_lesson_9/) - Случайный отзыв на главной
* [10 Урок](http://кофедизайн.рф/information/integration_adaptive_bootstrap_site_template_in_1c_bitrix_step_lesson_10/) - 2-х колоночный список 2 способами (список разделов и список элементов ИБ)
* [10+ Урок](http:/кофедизайн.рф/information/additional_workshop_on_integration_of_adaptive_Twitte_Bootstrap_site_template_in_1C-Bitrix_10_plus/) - собственный компонент 2-х колоночного списка элементов и\или разделов ИБ
* [11 Урок](http://кофедизайн.рф/information/integration_adaptive_twitte-Bootstrap_site_template_in_1C-Bitrix_step_by_step_lesson_11/) - Страница 404 ошибки



![Alt text](https://raw2.github.com/lexnekr/bitrixtemplate_stylish/master/bitrix/templates/stylish/screen.gif)


Входящие в шаблон сайта шаблоны компонетов
-------
* Компонент bitrix:news.list - шаблон main_slider (слайдер баннеров из инфоблока)
* Компонент bitrix:news.list - шаблон teasers (тизерные блоки из инфоблока)
* Компонент bitrix:news.list - шаблон main_page_newslist (список новостей на главной)
* Компонент bitrix:news.list - шаблон random_testimonials_on_main (список со случайной сортировкой для вывода отзывов)
* Компонент bitrix:news.list - шаблон 2_columns (2х колоночный список элементов инфоблока)
* Компонент bitrix:news.list - шаблон 1_column (1 колоночный список названий элементов инфоблока)
* Компонент bitrix:search.form - шаблон top (форма поиска для шапки)
* Компонент bitrix:search.form - шаблон stylish (универсальная форма поиска)
* Компонент bitrix:menu - шаблон top (верхнее меню с социльными иконками)
* Компонент bitrix:menu - шаблон bottom (нижнее меню)
* Компонент asd:subscribe.quick.form - шаблон bottom (БЫСТРАЯ Форма E-mail подписки)
* Компонент bitrix:subscribe.form - шаблон bottom (Форма E-mail подписки на базе системного компонента)
* Компонент bitrix:subscribe.edit - шаблон template (минимально модифицированная страница редактирования\подтверждения подписки)
* Компонент bitrix:catalog.section.list - шаблон 2_columns (2х колоночный список разделов инфоблока)
* Компонент bitrix:catalog.section.list - шаблон 1_column (1 колоночный древовидный список разделов инфоблока)


Входящие в шаблон Демо-Материалы (инфоблоки)
-------
* Все демо-материалы инфоблоков находятся в папке IMPORT_DATA.
* Название папки с данными соответсвует символьному коду инфоблока.
* Для импорта служит файл iblock.xml в папке с данными (содержит все необходимые настройки инфоблока и может служить для создания инфоблока с нуля).
* В папке iblock_files каждого инфоблока содержится набор файлов (например, картинок), подлежащий импорту. Все файлы автоматически перемещаются в upload при импорте.
* После импорта всех необходимых данных папку IMPORT_DATA со всем содержимым (включая картинки) следует удалить.

####СОДЕРЖИМОЕ:####

* MAIN_SLIDER
* TEASERS
* NEWS
* TESTIMONIALS


Входящие в шаблон Компонеты
-------
* asd:subscribe.quick.form - форма быстрой подписки Антона Долганина (http://dev.1c-bitrix.ru/community/webdev/user/11948/blog/5827/)
* coffeediz:elements_and_categories.list - 2-х колоночный список элементов и\или разделов инфоблоков

Входящие в шаблон Модули
-------
* asd.subscribequick - форма быстрой подписки Антона Долганина (http://dev.1c-bitrix.ru/community/webdev/user/11948/blog/5827/), Модуль из Marketplace 1С-Битрикс


Кодировка шаблона
-------
* Ветка Master - CP-1251
* Ветка UTF8 - UTF-8
