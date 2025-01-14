## Этап 4 проекта В04

__Задание:__  
1. Скачайте с репозитория исходные коды программ [display_text](../../code_examples/display_text) и [encoder](../../code_examples/encoder) и скопируйте их в соответсвующие поддиректории папки `./lab04`.
2. Самостоятельно скомпилируйте  программы `display_text` и `encoder` из исходных файлов.
3. Создайте makefile для каждой из программ, переименовав имена исполняемых файлов на `display_text_ФИО` и `encoder_ФИО`. Обязательные команды: all, clean.
4. Модернизируйте исходные коды программ следующим образом - `display_text_ФИО` - добавить к приему выводимого времени дату, а также добавить аргументы при вызове - указатель на именованный канал; `encoder_ФИО` - должна раз в секунду выдавать время и угол поворота (начиная от 0). Обе программы должны передавать данные в свои именованные каналы с помощью системого вызова write(). Скомпилирйте и отладьте работу программ. Время можно определить с помощью функции [clock_gettime()](https://ru.manpages.org/clock_gettime/2).
5. Модернизируйте bash-скрипт, запускающий эти программы, чтобы передавалось корректное число аргументов для программ `display_text_ФИО` и `encoder_ФИО`.
6. Скопируйте на ПК исходные коды, make файлы и bash-скрипт из `lab04`. Добавьте новое readme.md с инструкцией по сборке и запуску программ и сделайте коммит на сервер.
7. Продемонстрируйте преподавателю работу программ и bash-скрипта, а также созданный репозиторий. 
8. Подготовьте ответы на вопросы этапа 4 проекта.

__Список вопросов:__
1. Что значат флаги компиляции программ `display_text` и `encoder`?
2. Что делают команды all и clean в Ваших make файлах? Какие еще команды можно реализовать в Make файлах?
3. С помощью какой библиотеки определяется время в модернизированных программах?
4. Важен ли порядок передачи аргументов в программы при запуске и если да, то можно ли реализовать произвольную передачу аргументов?
5. Какого функционала еще не хватает Вашему комплекту ПО для выполнения требований курсового проекта?
6. Что такое объектные файлы и можно ли их удалить для успешного запуска программ `display_text_ФИО` и `encoder_ФИО`?
7. Можно ли переписать make файл таким образом, чтобы он собирал сразу две программы `display_text_ФИО` и `encoder_ФИО`?
8. Чем отличается Ваша инструкция к этой лабораторной работы от предыдущей?
9. Докажите, что Ваши исходные коды программ удовлетворяют [требованиям оформления исходных кодов](https://www.kernel.org/doc/html/v4.10/process/coding-style.html) на нескольких правилах.
10. Какой следующий этап доработки Вашего проекта?

__Порядок выполнения и сдачи [курсового проекта](var_04_task.md):__
1. [Этап проекта №1](var_04_stage_01.md)
2. [Этап проекта №2](var_04_stage_02.md)
3. [Этап проекта №3](var_04_stage_03.md)
4. [Этап проекта №4](var_04_stage_04.md)
5. [Этап проекта №5](var_04_stage_05.md)
6. [Этап проекта №6](var_04_stage_06.md)
7. [Этап проекта №7](var_04_stage_07.md)
8. [Этап проекта №8](var_04_stage_08.md)

