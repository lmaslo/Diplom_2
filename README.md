# Дипломный проект по автоматизации тестирования API для Stellarburgers. 
<a target="_blank" href="https://stellarburgers.nomoreparties.site/">Веб сайт Stellarburgers</a>


## :memo: Содержание:

- [Реализованные проверки](#boom-Реализованные-проверки)
- [Технологии](#classical_building-Технологии)
- [Запуск из терминала](#electron-Запуск-тестов-из-терминала)
- [Allure отчет](#bar_chart-Allure-отчет)

## :boom: Реализованные проверки

#### Создание пользователя
- ✓ Cоздать уникального пользователя
- ✓ Cоздать пользователя, который уже зарегистрирован
- ✓ Cоздать пользователя и не заполнить одно из обязательных полей

#### Логин пользователя
- ✓ Логин под существующим пользователем
- ✓ Логин с неверным логином и паролем

#### Изменение данных пользователя
- ✓ С авторизацией
- ✓ Без авторизации

#### Создание заказа
- ✓ С авторизацией
- ✓ Без авторизации
- ✓ С ингредиентами
- ✓ Без ингредиентов
- ✓ С неверным хешем ингредиентов

#### Получение заказов конкретного пользователя
- ✓ С авторизацией
- ✓ Без авторизации


## :classical_building: Технологии
<p align="center">
<img width="6%" title="Idea" src="/image/logo/Idea.svg">
<img width="6%" title="Java" src="image/logo/Java.svg">
<img width="6%" title="Selenide" src="image/logo/Selenide.svg">
<img width="6%" title="Allure Report" src="image/logo/Allure.svg">
<img width="6%" title="Maven" src="image/logo/maven.png">
<img width="6%" title="JUnit4" src="image/logo/junit.png">
<img width="6%" title="GitHub" src="image/logo/GitHub.svg">
</p>


## :electron: Запуск тестов из терминала

```
mvn clean test
```

## :bar_chart: Allure-отчет
<p align="center">
<img width="60%" title="Allure" src="image/logo/allure/allure1.PNG">
<img width="60%" title="Allure" src="image/logo/allure/allure2.PNG">
  </p>

