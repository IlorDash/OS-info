## Этап 6 проекта В05

__Задание:__  
1. Скачайте с репозитория исходные коды программ `gyro_angle_ФИО`, `step_motor_ФИО`, `combiner`, make файлы и bash-скрипт для их запуска, скопируйте их в соответсвующие поддиректории папки `./stage_06`.
2. Модернизируйте программу `combiner`, чтобы она в двух независимых потоках обменивалась сообщениями по именованным каналам с программами `gyro_angle_ФИО`, `step_motor_ФИО`, в третьем потоке обрабатывалось нажатие кнопок BUTTON0/BUTTON1 и вывод сообщений в стандартный поток, а в четвертом потоке осуществлялся прием команд из стандартного потока:
* `stop [название_программы]` - остановка программы, варианты - `gyro_angle_ФИО`, `step_motor_ФИО`, all;
* `start [название_программы]` - запуск программы, варианты - `gyro_angle_ФИО`, `step_motor_ФИО`;
* `set_angle [value]` - установка угла поворота.
3. Используйте для защиты данных мьютексы. Скомпилирйте и отладьте работу программ.
4. Скопируйте на ПК исходные коды, make файлы и bash-скрипт из `stage_06`. Добавьте новое readme.md с иснтрукцией по запуску программ и сделайте коммит на сервер.
5. Продемонстрируйте преподавателю работу программ и bash-скрипта, а также созданный репозиторий. 
6. Подготовьте ответы на вопросы к лабораторной работе.

__Список вопросов:__  
1. Каким образом создаются и заверщаются потоки, опишите способы взаимодействия между потоками?
2. Что произойдет, если не завершать работу потоков при завершении основного процесса?
3. Какие проблемы решает использование в многопоточном приложении мьютексов?
4. Чем отличаются потоки от процессов и перечислите потоки и процессы Вашего проекта?
5. Какую библиотеку для работы с потоками Вы использовали в своем проекте?
6. Можно ли было обойтись без мьютексов в Вашем проекте? Опишите ситуацию, при которой проект бы работал без мьютексов.
7. Сколько потоков работает в программах `gyro_angle_ФИО`, `step_motor_ФИО`?
8. Можно ли уменьшить количество потоков программе `combiner`?
9. Каким образом ОС осуществляет "одновременное" выполнение нескольких потоков и процессов на RPi?

__Порядок выполнения и сдачи [курсового проекта](var_05_task.md):__
1. [Этап проекта №1](var_05_stage_01.md)
2. [Этап проекта №2](var_05_stage_02.md)
3. [Этап проекта №3](var_05_stage_03.md)
4. [Этап проекта №4](var_05_stage_04.md)
5. [Этап проекта №5](var_05_stage_05.md)
6. [Этап проекта №6](var_05_stage_06.md)
7. [Этап проекта №7](var_05_stage_07.md)
8. [Этап проекта №8](var_05_stage_08.md)