# Домашнее задание к занятию «Упаковка приложения в контейнер»

Выполнив это задание, вы сможете запускать контейнеры Docker и упаковывать свои приложения в контейнеры.

### Цель задания

1. Сделать свой контейнер.
2. Научиться создавать контейнеры.
3. Научиться упаковывать приложения в контейнеры.

------

### [Задание 1](01)

#### Установка Docker

1. Установите Docker для вашей операционной системы.
2. Проверьте работу, установив дистрибутив Ubuntu 16.04, с компиляторов gcc и любым текстовым редактором.
3. Соберите консольное приложение «Hello world».

 <h2 align="center">Сборка образа</h2>

```docker build -t hello_world:v1 .```

<h2 align="center">Запуск контейнера</h2>

```docker run --name hello_world -it hello_world:v1```

### [Задание 2](02)

#### Работа с образами

1. Упакуйте в контейнер любой проект из выполненных вами ранее домашних заданий для различных компиляторов — gcc и clang.
2. Проверьте их работу.

------

### Правила приёма домашней работы

Чтобы сдать домашнее задание, прикрепите в личном кабинете ссылку на ваш репозиторий.

### Критерии оценки домашней работы

1. В личном кабинете прикреплена ссылка на репозиторий с кодом для заданий 1 и 2.
2. В ссылке содержится код, который при запуске выполняет описанный в задании алгоритм.

