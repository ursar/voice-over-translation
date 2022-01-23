# Закадровый перевод видео

Закадровый перевод видео не только в YandexBrowser.
Очень признателен, **[Yandex.Translate](https://translate.yandex.ru/)** & **[sodapng](https://github.com/sodapng)**. Спасиб <3

## Установка веб-сервера и расширения:

1. Установите расширение **[Tampermonkey](https://violentmonkey.github.io/get-it/)**
2. Установите YandexBrowser и NodeJS v16.x
3. В настройках YandexBrowser **отключите работу в фоне**, а так же **автозапуск**
4. Скачайте архив с исходником веб-сервера
![howto download](https://github.com/ilyhalight/voice-over-translation/blob/master/howto_download.png "howto_download")
5. Заполните свои пути к YandexBrowser в конфиг-файле (он находится тут: "voice-over-translation/web-server/config/default.json")
6. Установите все модули необходимые для работы веб-сервера. Для этого, находясь в папке "web-server", пропишите в консоли: ```npm i``` и дождитесь установки всех модулей.
7. Запустите веб-сервер. Для этого, находясь в папке "web-server", пропишите в консоли: ```npm run start```
8. **[«Установите Скрипт»](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/vot.user.js)**

Примечание: Во время работы веб-сервера в консоли могут вылетать какие-то ошибки. Это нормально
![example btn](https://github.com/ilyhalight/voice-over-translation/blob/master/example.png "btn")
