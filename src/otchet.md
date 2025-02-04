## Часть 1 Установка и настройка
-Проверка версии линукс

![Проверка весрии линукса](images/linux_version1.jpg)
![Проверка весрии линукса](images/linux_version2.jpg)
*Скриншот 1, 2: Показаны версия линукса  и настройки

## Часть 2: Создание пользователя
- Создание нового пользователя (Дополняя личные данные)
- Проверка естть ли новый пользователь

![Создание нового пользователя (пароля и логин)](images/create_newuser.jpg)
![Создание нового пользователя (доп. информация)](images/create_newuser_plus_info.jpg)

## Часть 3: Настройка сети ОС
- Задать название машины user-1
- Установка временных зон (Москва, Россия)
- Получение ip адреса от DHCP сервера
- Проверка пинга удаленного хотса ya.ru и 1.1.1.1

![Создание хоста user-1 и определение временной зоны](images/user-1_+timezone.jpg)
![Проверка айпи](images/ip_command.jpg)

Интерфейс lo - это loopback-интерфейс, который используется для тестирования и отладки сетевых приложений на локальном компьютере. Он всегда имеет IP-адрес 127.0.0.1.

![Проверка айпи адреса](images/ip_addr_command.jpg)

DHCP (Dynamic Host Configuration Protocol) - это сетевой протокол, который автоматически назначает IP-адреса и другие сетевые параметры (например, шлюз и DNS-серверы) устройствам в сети.

![Вывод даных айпи адресов шлюзов](images/ip_addresses.jpg)
![Настройка в nano айпи адреса](images/nano_settings.jpg)
![Перезапуск айпи адреса](images/Netplan_reset.jpg)
![Проверка айпи соединения с ya.ru](images/ping_ya.ru_checking.jpg)

## Часть 4: Обновление ОС
- Обновление системы (скачивание установочных файлов)
- Обновление системы (установление файлов)

![Команда sudo apt update](images/sudo_apt_update.jpg)
![Команда sudo apt upgrade](images/sudo_apt_upgrade.jpg)

## Часть 5: Использование команды sudo
- Задать полномочия sudo для нового аккаунта
- Поменять hostname для нового аккаунта
- Проверить предоставленно ли

Команда sudo (SuperUser DO) предоставляет привилегированный доступ к выполнению команд от имени суперпользователя или других пользователей, обладающих правами sudo. Это позволяет выполнить определенные операции, требующие повышенных привилегий, без необходимости полного входа в систему под суперпользователем.

![Передаем возможность использования sudo для нового аккаунта](images/Sudo_giving.jpg)
![Меняем хост ОС от имени пользователя](images/giving_hostname.jpg)
![Проверка](images/sudo_checkong_newuser.jpg)

## Часть 6: Установка  и настройка службы времени
- Скачать библиотеку время/дата
- Поверка времени и даты

![Скачивание библиотеки](images/sudo_install_ntp_1.jpg)
![Скачивание библиотеки](images/sudo_install_ntp_2.jpg)
![Вывод даты и время](images/time_date_show.jpg)

## Часть 7: Установка и использования текстовых редакторов
- Скачать текстовые редакторы
- Создать файлы, используя текстовые редакторы и вписывание (сохраняя)
- Редактировать файл, не сохраняя

![Скачивание текстовых редакторов 1](images/install_text_edit_1.jpg)
![Скачивание текстовых редакторов 2](images/install_text_edit_2.jpg)
![Создание файла и запись VIM 1](images/vim_file_1.jpg)
![Создание файла и запись VIM 2](images/vim_file_2.jpg)
![Создание файла и запись NANO 1](images/nano_file_1.jpg)
![Создание файла и запись NANO 2](images/nano_file_2.jpg)
![Создание файла и запись MCEDIT](images/MCedit_file.jpg)
![Запись файла (не сохраняя) VIM 1](images/vim_file_3.jpg)
![Запись файла (не сохраняя) VIM 2](images/vim_file_4.jpg)
![Запись файла (не сохраняя) VIM 3](images/vim_file_5.jpg)
![Запись файла (не сохраняя) NANO 1](images/nano_file_3.jpg)
![Запись файла (не сохраняя) NANO 2](images/nano_file_4.jpg)
![Запись файла (не сохраняя) MCEDIT 1](images/MCedit_file_2.jpg)
![Запись файла (не сохраняя) MCEDIT 2](images/MCedit_file_3.jpg)
![Запись файла (не сохраняя) MCEDIT 3](images/MCedit_file_4.jpg)

## Часть 8: Установка и базовая настройка сервиса SSHD
- Обновление системы
- Установка библиотеки SSHD
- Настройка sshd
- Настройка sshd порт на 2022
- Перезапуск системы sshd
- Вывод

![Проверка наличия обновлений](images/update_8.jpg)
![Проверка](images/systemctl_sshd.jpg)
![Скачивание библиотеки](images/install_sshd.jpg)
![Вывод 1](images/chapter8_vivody_1.jpg)
![Вывод 2](images/chapter8_vivody_2.jpg)
![Вывод 3](images/chapter8_vivody_3.jpg)

## Часть 9: Установка и использование утилит top, htop
- Установка утилит top, htop
- Отчет top
- uptime
- кол-во автор. пользователей
- общая загрузка системы
- загрузка cpu
- загрузка памяти
- pid процесса занимающего больше всего памяти
- pid процесса, занимающего больше всего процессорного времени
- Отчет htp
- PID
- PERCENT_CPU
- PERCENT_MEM
- TIME
- sshd процесс
- clock, uptime

![Отчет top](images/top.jpg)
Uptime: 16:24:09 up 6 min
Количество авторизованных пользователей: 1 user
Общая загрузка системы: load average: 0.44, 0.48, 0.28
Общее количество процессов: Tasks: 161 total
Загрузка CPU: %Cpu(s): 0.0 us, 0.0 sy, 0.0 ni, 99.7 id, 0.1 wa, 0.0 hi, 0.1 si, 0.0 st
Загрузка памяти: MiB Mem: 7940.7 total, 7005.5 free, 449.8 used, 726.8 buff/cache

![Отчет htop](images/htop.jpg)
![Отчет по PID](images/F6_PID.jpg)
![Отчет по CPU](images/F6_PERCENT_CPUU.jpg)
![Отчет по памяти](images/F6_PERCENT_MEM.jpg)
![Отчет по времени](images/F6_PERCENT_TIME.jpg)
![Отчет по SSHD](images/F4_SSHD.jpg)
![Отчет по syslog](images/F3_SYSLOG.jpg)
![Отчет по дате, хост имени и времени](images/DATE_HOSTNAME_TIME.jpg)

## Часть 10: Использование утилиты fdisk
- Запуск команды fdisk -l

![Запуск утилиты fdisk](images/sudo_fdisk-l.jpg)
![Команда свободного части диска](images/free-h.jpg)

## Часть 11: Использование утилиты df
- Запуск команды df
- Запуск команды df -Th

![Запуск утилиты df, df -h, df -Th](images/utility_df.jpg)

Команда df:

Размер раздела: 14G
Размер занятого пространства: 4.4G
Размер свободного пространства: 8.6G
Процент использования: 34%
Единица измерения: Гигабайты (G)
Команда df -Th:

Размер раздела: 14G
Размер занятого пространства: 4.4G
Размер свободного пространства: 8.6G
Процент использования: 34%
Тип файловой системы: ext4

## Часть 12: Использование утилиты du
- Запуск команды du
- Вывод папок /home/
- Вывод папок /var/
- Вывод папок /var/log/

![Использование команды du](images/du.jpg)
![Просмотр папки home](images/du_home.jpg)
![Просмотр папки home](images/home_sh.jpg)
![Просмотр папки var](images/du_var.jpg)
![Просмотр папки var](images/var_sh.jpg.jpg)
![Просмотр папки var/log](images/var_log*.jpg.jpg)

## Часть 13: Установка и использование утилиты ncdu
- Установить утилиту ncdu
- Просмотреть папки home, var, var/log

![Скачивание утилиты ncdu](images/install_ncdu.jpg)
![Проверка папки home](images/ncdu_home.jpg)
![Проверка папки home без интерфейса](images/ncdu_home_less.jpg)
![Проверка папки var](images/ncdu_var.jpg)
![Проверка папки var без интерфейса](images/ncdu_var_less.jpg)
![Проверка папки var/log](images/ncdu_var_log.jpg)
![Проверка папки var/log без интерфейса](images/ncdu_var_log_less.jpg)

## Часть 14: Работа с системными журналами
- Прочитать информацию внутри файла dmesg
- Прочитать информацию внутри файла syslog
- Прочитать информацию внутри файла auth.log
- Заменить статус авторизации на успешно
- Проверить файд auth.log на наличие статуса
- Отрыть журнал sshd и найти последний перезапуск

![Файл /var/log/dmesg](images/dmesg.jpg)
![Файл /var/log/syslog](images/syslog.jpg)
![Файл /var/log/auth.log](images/auth.log.jpg)
![Добавляем статус Успешно](images/accepted.jpg)
![Вывод системного журнала после перезапуска системы sshd](images/sys_journal_1.jpg)
![Вывод системного журнала после перезапуска система sshd (в 18:58 видно перезапуск sshd)](images/sys_journal_18:58.jpg)

## Часть 15: Использование планировщика заданий CRON
- Найти в журнале cron 
- Вывести на экран строчку, которая выводит "uptime"
- После добавления строки перезапуск и собстевенно вывод

![Открытие cron](images/chapter_15_1.jpg)
![Открытие cron 1 файл](images/chapter_15_2.jpg)
![Дбавление строки](images/chapter_15_3.jpg)
![Проверяем наличие строки](images/chapter_15_4.jpg)
![Проверка выводов](images/chapter_15_5.jpg)