# ПУЛЬС

Лендинг школы бокса

Откройте index.html в браузере или разместите файл в корне GitHub Pages
CSS, JavaScript, изображения и трёхсекундное видео встроены в HTML
Сборка и установка зависимостей не нужны

## В этой версии

- Один удар с искрами и возврат руки в защиту
- Затемнение фона и центрированная надпись «Не жди момента / Делай момент»
- Одна кнопка на первом экране
- Шрифты Unbounded и Onest с кириллицей
- Направления в широких полосах, команда со смещением карточек и абонементы в виде пропусков
- Тексты без точек и длинных тире
- Адаптивная навигация, проверка формы, пауза анимации и поддержка reduced motion

## Перед приёмом реальных заявок

В index.html найдите const CONFIG

- leadEndpoint содержит HTTPS-адрес обработчика заявок
- phone и address содержат реальные контакты школы
- socials содержит массив ссылок вида {label: 'ВКонтакте', url: 'https://vk.com/имя'}
- prices содержит утверждённую стоимость абонементов kids, beginner и pro

Пока leadEndpoint пуст, форма показывает деморежим и ничего не отправляет
Обработчик получает POST JSON с полями name, phone, direction, plan и consent
Для другого домена необходимо разрешить CORS
Ответ HTTP 2xx должен означать принятую заявку

Портреты тренеров заменены стоковыми иллюстрациями с явной подписью
Имена, регалии и цифры взяты из исходного брифа
Перед использованием для настоящего клуба проверьте эти данные и добавьте реквизиты оператора персональных данных

## Проверка

Проверены видео, остановка в финальной стойке, меню, выбор абонемента, ошибки формы и демонстрационное заполнение
Проверены экраны 1280, 390 и 320 px
JavaScript проверен через node --check

## Шрифты

[Unbounded](https://github.com/w3f/unbounded)

[Onest](https://github.com/simpals/onest)

## Фотографии

[Frankie Cordoba / Unsplash](https://unsplash.com/fr/photos/une-photo-en-noir-et-blanc-de-deux-hommes-sur-un-ring-de-boxe-apW3MUh4FFE)

[Michael Starkie / Unsplash](https://unsplash.com/photos/a-man-in-a-gym-wearing-boxing-gloves-F412aTVczu0)

[Gustavo Fring / Pexels](https://www.pexels.com/photo/a-man-wearing-black-boxing-gloves-6720430/)

[Annushka Ahuja / Pexels](https://www.pexels.com/photo/a-man-wearing-a-boxing-gloves-7992074/)

[Tima Miroshnichenko / Pexels](https://www.pexels.com/photo/a-portrait-of-a-boxer-5750958/)

[BYB BYB / Pexels](https://www.pexels.com/photo/portrait-of-boxer-19115238/)
