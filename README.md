# ZA Gmod Loading Screen
Это модифицированный экран загрузки для Garry’s Mod, делал его для своего MilitaryRP сервера. 
Этот экран загрузки показывает подсказки, которые синхронизированы со сменой заднего фона, а так же воспроизводит музыку.


Огромное спасибо Габриэлю Ванзеку (он же CodeBrauer) за вдохновение!
Оригинальный экран загрузки: https://github.com/CodeBrauer/gmod-loadingscreen

## Установка
Для установки этого экрана загрузки вам нужно скачать и распаковать архив с репозитория в любую папку на вашем веб-сервере. 
Далее вам понадобится сделать несколько простых шагов:
- поместите несколько музыкальных файлов в формате .ogg в папку music. Они должны быть названы 1.ogg, 2.ogg и 3.ogg и тд...
- поместите несколько картинок в формате .jpeg в папку img. Они должны быть названы 1.jpeg, 2.jpeg и 3.jpeg и тд...
- поместите несколько гифок для подсказок в формате .gif в папку gifs. Они должны быть названы 1.gif, 2.gif и 3.gif и тд...
- измените подсказки в строках 20-33 в `index.php`, так же привязав к ним гифки.
- в строке 86-87 измените время изменения подсказок и изображений.

После этого вы можете установить этот экран загрузки для вашего сервера Garry’s Mod, указав в консоли или в файле `server.cfg` следующую команду:

`sv_loadingurl “http://your-web-server.com/path/to/loading-screen/index.php?steamid=%s&mapname=%m”`

Где `your-web-server.com` - это адрес вашего веб-сервера, а path/to/loading-screen - это путь к папке с экраном загрузки.

## Особенности
- Адаптивный дизайн, который подходит для разных разрешений экрана и устройств.
- Скрипт для отображения подсказок и изображений.
- Музыкальное сопровождение, которое поднимает настроение и скрашивает ожидание.

## Лицензия
Этот экран загрузки распространяется под лицензией MIT 3, которая позволяет свободно использовать, изменять и распространять этот код при условии указания авторства.

