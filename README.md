# Приложение для заказа столика в баре
Данное приложение разработано для заказа столика и еды в баре
### Содержание
- [Технологии](##технологии)
- [Использование](#использование)
- [Тестирование](#тестирование)
- [Contributing](#contributing)
- [FAQ](#faq)
- [To do](#to-do)
- [Команда проекта](#команда-проекта)
- [Источники](#источники)

## Технологии
- [Android Studio 2024](https://developer.android.com/studio)
- [Kotlin](https://kotlinlang.org/)
- [Jetpack Compose](https://www.jetbrains.com/ru-ru/lp/compose-multiplatform/)

## Использование
Для работы с приложением необходимо зарегистрироваться в системе 

<img src="https://github.com/orderyoo/maximbar/assets/122743400/c00a649c-21fc-4380-8003-1731467b13ee" width="200" />

После входа будет отображён главный экран:

<img src="https://github.com/orderyoo/maximbar/assets/122743400/ca53c678-f629-4889-ba85-04838aa669c8" width="200" />


Тут можно задать сортировку:

<img src="https://github.com/orderyoo/maximbar/assets/122743400/5810cefa-0526-46e3-be09-9eb76badefd4" width="200" />


Выбрав стол нажатием открывается экран заказа стола

<img src="https://github.com/orderyoo/maximbar/assets/122743400/d69a91ab-9a6f-4d52-b601-cc5be4e8ab91" width="200" />


Тут можно добавить продукты в корзину

<img src="https://github.com/orderyoo/maximbar/assets/122743400/e7e3d0ec-daf4-491f-93e1-2c15da38d8ed" width="200" />

## Разработка
### Тестирование
В проекте использовались следующие виды тестирования: Интеграционное тестирование 
Итоги тестирования:
### Итеграционное тестирование 

Граф программы:

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/c9eedc31-894c-4c75-948b-19c54742e5bd)

Тестовые пути:

-T1: 1-2-3-4-5-6 
-T2: 1-2-3-4-8-5-6 
-T3: 1-2-3-4-8-9-5-6 
-T4: 1-2-3-11-12-6 
-T5: 1-2-3-11-13-6 
-T6: 1-2-3-14-15-6 
-T7: 1-2-3-14-16-6 
-T8: 1-3-4-5-6 
-T9: 1-3-4-8-5-6 
-T10: 1-3-4-8-9-5-6 
-T11: 1-3-11-12-6 
-T12: 1-3-11-13-6 
-T13: 1-3-14-15-6 
-T14: 1-3-14-16-6 
-T15: 1-2-3-7-4-5-6 
-T16: 1-2-3-7-4-8-5-6 
-T17: 1-2-3-7-4-8-9-5-6 
-T18: 1-2-3-7-11-12-6 
-T19: 1-2-3-7-11-13-6 
-T20: 1-2-3-7-14-15-6 
-T21: 1-2-3-7-14-16-6 
-T22: 1-3-7-4-5-6 
-T23: 1-3-7-4-8-5-6 
-T24: 1-3-7-4-8-9-5-6 
-T25: 1-3-7-11-12-6 
-T26: 1-3-7-11-13-6 
-T27: 1-3-7-14-15-6 
-T28: 1-3-7-14-16-6 
-T29: 1-2-3-4-10-5-6 
-T30: 1-2-3-4-10-8-5-6 
-T31: 1-2-3-4-10-8-9-5-6 
-T32: 1-3-4-10-5-6 
-T33: 1-3-4-10-8-5-6 
-T34: 1-3-4-10-8-9-5-6

### Тест-кейсы
Таблица 1 – Тест-кейс авторизация 

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/6b5e6c0b-d02d-443c-81f2-74fd557f5c70)

Таблица 2 – Тест-кейс выбора просматриваемых столов

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/fbe9f944-f9e1-4153-ad13-c547e545f6dc)

Таблица 3 – Тест-кейс фильтрации столов

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/5af42a71-983a-4bd5-bfad-534028b89053)

Таблица 4 – Тест-кейс добавления продукта в корзину

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/a6c017bb-bc69-4df9-b67b-1f89a9ef429b)

Таблица 5 – Тест-кейс удаления продукта из корзины

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/1fa9d73c-4ee7-4fab-8c59-f2106a082466)

Таблица 6 – Тест-кейс заказа

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/f60592c5-e27a-4012-b063-c6d505fba764)

Таблица 7 – Тест-кейс добавления продукта в меню

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/db5f07f2-fe16-4b49-9580-2d4e62ffd07e)

Таблица 8 – Тест-кейс удаления продукта из меню

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/83e73470-e492-4301-91b2-6ebbe74cc819)

Таблица 9 – Тест-кейс добавления стола

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/3b0765cc-29fb-40ec-acb3-b18256ae0455)

Таблица 10 – Тест-кейс удаления стола

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/87169d0e-9387-4a6f-a787-1001836580f6)

Таблица 11 – Просмотр всех заказов

![image](https://github.com/PoluektovaDarya/maximbar-master/assets/123874713/bc1cada9-11bb-4616-9ce4-e02a51d2d286)


## Contributing
Сообщения о багах и ошибках присылать на почту: markovmaks895@gmail.com

## FAQ 
### Что у вас есть в баре?
- Сплошные раритеты по доступным ценам!
### Зачем вы разработали этот проект?
- меня забайтил Артём

  ## Команда проекта
- [Марков Максим](https://t.me/order_yo) — android разработчик, страдалец и мученник
- [Дарья Полуэктова](https://t.me/Sychugun) — ещё один android разработчик, страдалец и мученник
- [Артемий Доброхотов](https://t.me/ArtikDemonik) — серверный лазутчик

## Источники 

https://developer.android.com/
https://open.ai/chat.gpt
