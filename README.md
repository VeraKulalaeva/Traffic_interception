# Traffic interception via Charles Proxy

В рамках домашнего задания проводилось тестирование <a href="https://github.com/osukhorukova/git">интернет магазина</a> с использованием сниффера  Charles Proxy

Необходимо было:

1) <a href="https://disk.yandex.ru/i/jv0oj5OaMnVDmA">Изменить количество товаров</a> в корзине - в запросе отправляется "2" товара, должны вернуться "500".

2) Смоделировать ситуацию, при которой при обращении к ресурсу <a href="https://disk.yandex.ru/i/MTxmKgOBFnpFGQ">сервер вернет статус-код 403</a>.

3) <a href="https://disk.yandex.ru/i/kSzwkSasqualig">Перебросить запрос</a> с окружения Prod на QA.

А также изменять данные запросов, уходящих с мобильного устройства Android:

4) <a href="https://disk.yandex.ru/i/L2pt7qIwS5b95Q">Удалить товары из корзины</a> в уже известном интернет магазине.

5) Смоделировать ситуацию, при которой при обращении к ресурсу пользователь увидит в браузере <a href="https://disk.yandex.ru/i/Guu3YnS0vWszPQ">любую картинку</a>.

6) Продемонстрировать информацию об <a href="https://disk.yandex.ru/i/boZ-zqmLIU4v4A">используемом устройстве Android</a>.