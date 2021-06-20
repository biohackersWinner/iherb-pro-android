Реализованная функциональность
------------
<ul>
    <li>Экран профиля</li>
    <li>Экран списка рецептов от врача (нутриолога)</li>
    <li>Реализован модуль обработки изображения с устройства и отправки на <a href="https://cloud.yandex.ru/docs/vision/operations/ocr/text-detection">Yandex Vision OCR</a></li>
    <li>Реализован модуль обработки изображения с устройства и отправки на <a href="https://convertio.co/">Convert.io</a> (был взят изначально, но не устроило качество и скорость распознавания)</li>
    <li>Обработка изображения рецепта, распознание текста при помощи Yandex Vision, а также поиск и сопоставление с группами БАДов</li>
</ul>

Особенность проекта в следующем:
------------
<ul>
    <li>Вы можете указывать приложению файлы (изображения) рецептов, предоставляемых врачом, картинка сохраняется в локальном хранилище, обрабатывается и сохраняет метаинформацию</li>
</ul>

Основной стек технологий::
------------
<ul>
    <li>Kotlin</li>
    <li>Jetpack Navigation, ViewModel</li>
    <li>Material Design Components</li>
    <li>Hilt</li>
    <li>Yandex Vision</li>
    <li>Git</li>
</ul>

СРЕДА ЗАПУСКА
------------
1) запуск приложения производиться в Android Studio;
2) Для проверки работоспособности можно использовать изображение из репозитория (или сфотографировать экран):
![](docs/20210619_181821.jpg)

УСТАНОВКА
------------
1) скачайте репозиторий;
2) откройте проект в Android Studio;
3) Запустить проект

РАЗРАБОТЧИК

<h4>Фридон Данелян Android https://t.me/fridonium</h4>