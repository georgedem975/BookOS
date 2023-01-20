# Управление процессами.
---

Job (задание, контрольная группа) - совокупность процессов с заданными для нее квотами ресурсов.

Process (Процесс) - совокупность набора исполняемых команд, ассоциированных с ним ресурсов и контекста исполнения, находящиеся под управлением ОС.

Thread (Поток) - отдельный набор команд и контекст, имеющие доступ к одному адресному пространству.

Нить (Волокно) - (облегченный поток) совокупность набора команд, находящихся под управлением пользовательского приложения.

![1](https://github.com/georgedem975/BookOS/blob/master/chapter_four/assets/1.png)

__Функции подсистемы управления процессами:__
1. Создание процессов и потоков
2. Обеспечение ресурсами процессов
3. Изоляция процессов друг от друга
4. Планирование процессов и потоков
5. Диспетчеризация
6. Взаимодействие процессов между собой
7. Синхронизация
8. Уничтожение процессов

__Структура процесса:__
+ идентификатор (PID, PPID, UID)
+ состояние процесса
+ история

<p align="center"> <a href=https://github.com/georgedem975/BookOS/blob/master/chapter_three/README.md>⬅️</a><a href=https://github.com/georgedem975/BookOS/blob/master/README.md>⏺</a><a href=>➡️</a></p>