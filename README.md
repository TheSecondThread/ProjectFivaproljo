# Project Fivaproljo

## Системные требования 
* Linux или macOS
* CMake 3.15
* C++17
* QT 5.14.

Работа над проектом велась в [этом репозитории](https://github.com/TheSecondThread/FivaproljoTasks).

## Сборка проекта
На Linux - в CMake указать путь до библиотеки QT.
В папке проекта:
```
cmake .
make
./demo
```
## Запуск
Чтобы начать игру по локальной сети, выберите `Two players`. Порт для подключения к серверу - **5051**.

## Описание проекта

Платформер, в котором задача игрока - покрасить наибольшее количество блоков в свой цвет за ограниченное время. Возможна игра по локальной сети для двух игроков.
