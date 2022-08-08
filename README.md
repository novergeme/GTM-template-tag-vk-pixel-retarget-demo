# Добро пожаловать! 

Это инструкция по установке и настройке шаблона  VK Pixel&Retarget DEMO для Google Tag Manager.


## 1. Установите тег VK Pixel&Retarget DEMO

Установить тег вы можете из [Галереи ](https://tagmanager.google.com/gallery/#/?page=1) шаблонов GTM (воспользуйтесь поиском и найдите шаблон по названию «VK Pixel&Retarget DEMO», [инструкция по использованию](https://support.google.com/tagmanager/answer/9454109?hl=ru) Галереи шаблонов). Или [скачайте шаблон](https://github.com/novergeme/GTM-template-tag-vk-pixel-retarget-demo/archive/refs/heads/main.zip) напрямую из github и установите в GTM через «Импорт» шаблонов, [инструкция по импорту](https://developers.google.com/tag-manager/templates?hl=ru#export_and_import).

## 2. Настройка тега в режиме «Конверсии (Goal)»

2.1. В поле «Укажите ID VK пикселя» впишите ваш ID VK пикселя;

2.2. Выбирете режим «Конверсии (Goal)»;

2.3. В выпадающем списке выбирите событие, которое хотите отправлять в VK (Например add_to_cart);

2.4. Если событие имеет ценность, то установите галочку «Указать ценность конверсии Value»;

2.4.1. В появившемся текстовом поле укажите «переменную уровня данных», которая возвращает число ценности события;

2.4.2. Если хотите чтобы ценность события посчиталась автоматически, то поставье галочку в поле «Посчитать value из dataLayer», но в таком случае - ваша «переменная уровня данных» должна указывать на массив например ecommerce.checkout.products;

## 3. Настройка тега в режиме «Сбор аудиторий (Audience)»

3.1. В поле «Укажите ID VK пикселя» впишите ваш ID VK пикселя;

3.2. Выбирете режим «Сбор аудиторий (Audience)»;

3.3. Если хотите отправить событие Hit, то выбирите настройку «Настроить URL и Title (Hit)»;

3.3.1. Поле URL установленно по умолчанию, в поле Tittle укажите переменную, которая возвращает название посещаемой страницы;

3.4. Параметры event, audience и device_id можете указать выборочно или сразу все;

3.4.1. Параметыры event, audience, device_id можете использовать совместно с URL и Title. В таком случае за одно будет отправлено и событие Hit;

## 4. Настройка тега в режиме «Динамический ретаргетинг (ProductEvent)»

4.1. Режим «Динамический ретаргетинг (ProductEvent)» достпен только в Full версии, [подробнее](https://novergeme.ru/vk_pixel_retarget?utm_source=github&utm_medium=gtm&utm_campaign=instruction4_1) на сайте разработчика;

4.2. Вы можете посмотреть UI-интерфейс режима «Динамический ретаргетинг (ProductEvent)» и увидеть какие поля используются в Full версии;

## 5. Разделе «О проекте»

5.1. Инструкция: вам доступно 12 видеоинструкций в режиме скринкаста (видео с экрана):  [ссылка на YouTube](https://youtube.com/playlist?list=PLy7BYWCGI_atdK3qm9rbp2PNaAKfSGp0T);

5.2. Разработчик:  [ссылка на сайт разработчика](https://novergeme.ru/vk_pixel_retarget)  , эта ссылка ведёт на web-страницу сайта разработчика, которая посвящена данному шаблону.
