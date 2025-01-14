## Этап 4 проекта В10

__Задание:__  
1. Скачайте с репозитория исходные коды программ [step_motor](../../code_examples/step_motor), [keypad](../../code_examples/keypad) и [rangefinder_gp2y](../../code_examples/rangefinder_gp2y) и скопируйте их в соответсвующие поддиректории папки `./stage_04`.
2. Самостоятельно скомпилируйте  программы `step_motor`, `keypad` и `rangefinder_gp2y` из исходных файлов.
3. Создайте makefile для каждой из программ, переименовав имена исполняемых файлов на `step_motor_ФИО` и `rangefinder_gp2y_ФИО`. Обязательные команды: all, clean.
4. Модернизируйте исходные коды программ следующим образом - `step_motor_ФИО` - должна работать без остановки и принимать данные об угле поворота через именованных канал `keypad_data`; `rangefinder_gp2y_ФИО` - также добавить время выдаваемого отсчета АЦП и указатель на именованный канал `gp2y_data`. Обе программы должны обмениваться с именованными каналами с помощью системных вызовов read()/write(). Скомпилирйте и отладьте работу программ. Время можно определить с помощью функции [clock_gettime()](https://ru.manpages.org/clock_gettime/2).
5. Модернизируйте bash-скрипт, запускающий эти программы, чтобы передавалось корректное число аргументов для программ `step_motor_ФИО` и `rangefinder_gp2y_ФИО`.
6. Скопируйте на ПК исходные коды, make файлы и bash-скрипт из `stage_04`. Добавьте новое readme.md с инструкцией по сборке и запуску программ и сделайте коммит на сервер.
7. Продемонстрируйте преподавателю работу программ и bash-скрипта, а также созданный репозиторий. 
8. Подготовьте ответы на вопросы этапа 4 проекта.

__Список вопросов:__
1. Что значат флаги компиляции программ `step_motor` и `rangefinder_gp2y`?
2. Что делают команды all и clean в Ваших make файлах? Какие еще команды можно реализовать в Make файлах?
3. С помощью какой библиотеки определяется время в модернизированных программах?
4. Важен ли порядок передачи аргументов в программы при запуске и если да, то можно ли реализовать произвольную передачу аргументов?
5. Какого функционала еще не хватает Вашему комплекту ПО для выполнения требований курсового проекта?
6. Что такое объектные файлы и можно ли их удалить для успешного запуска программ `step_motor_ФИО` и `rangefinder_gp2y_ФИО`?
7. Можно ли переписать make файл таким образом, чтобы он собирал сразу две программы `step_motor_ФИО` и `rangefinder_gp2y_ФИО`?
8. Чем отличается Ваша инструкция к этой лабораторной работы от предыдущей?
9. Докажите, что Ваши исходные коды программ удовлетворяют [требованиям оформления исходных кодов](https://www.kernel.org/doc/html/v4.10/process/coding-style.html) на нескольких правилах.
10. Какой следующий этап доработки Вашего проекта?

__Порядок выполнения и сдачи [курсового проекта](var_10_task.md):__
1. [Этап проекта №1](var_10_stage_01.md)
2. [Этап проекта №2](var_10_stage_02.md)
3. [Этап проекта №3](var_10_stage_03.md)
4. [Этап проекта №4](var_10_stage_04.md)
5. [Этап проекта №5](var_10_stage_05.md)
6. [Этап проекта №6](var_10_stage_06.md)
7. [Этап проекта №7](var_10_stage_07.md)
8. [Этап проекта №8](var_10_stage_08.md)

