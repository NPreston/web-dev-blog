Очень полезные команды Linux на одном листе
===========================================
* **[Системная информация](#%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%BD%D0%B0%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F)**
* **[Остановка системы](#%D0%9E%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B)**
* **[Файлы и директории](#%D0%A4%D0%B0%D0%B9%D0%BB%D1%8B-%D0%B8-%D0%B4%D0%B8%D1%80%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%B8%D0%B8)**
* **[Поиск файлов](#%D0%9F%D0%BE%D0%B8%D1%81%D0%BA-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2)**
* **[Монтирование файловых систем](#%D0%9C%D0%BE%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D1%8B%D1%85-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC)**
* **[Дисковое пространство](#%D0%94%D0%B8%D1%81%D0%BA%D0%BE%D0%B2%D0%BE%D0%B5-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%BE)**
* **[Пользователи и группы](#%D0%9F%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B8-%D0%B8-%D0%B3%D1%80%D1%83%D0%BF%D0%BF%D1%8B)**
* **[Выставление/изменение полномочий на файлы](#%D0%92%D1%8B%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%BB%D0%BD%D0%BE%D0%BC%D0%BE%D1%87%D0%B8%D0%B9-%D0%BD%D0%B0-%D1%84%D0%B0%D0%B9%D0%BB%D1%8B)**
* **[Специальные атрибуты файлов](#%D0%A1%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D0%B0%D1%82%D1%80%D0%B8%D0%B1%D1%83%D1%82%D1%8B-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2)**
* **[Архивирование и сжатие файлов](#%D0%90%D1%80%D1%85%D0%B8%D0%B2%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B8-%D1%81%D0%B6%D0%B0%D1%82%D0%B8%D0%B5-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2)**
* **[RPM пакеты (Fedora, Red Hat и тому подобное)](#rpm-%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-fedora-red-hat-%D0%B8-%D1%82%D0%BE%D0%BC%D1%83-%D0%BF%D0%BE%D0%B4%D0%BE%D0%B1%D0%BD%D0%BE%D0%B5)**
* **[YUM - средство обновления пакетов (Fedora, RedHat и тому подобное)](#yum---%D1%81%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D0%BE%D0%B2-fedora-redhat-%D0%B8-%D1%82%D0%BE%D0%BC%D1%83-%D0%BF%D0%BE%D0%B4%D0%BE%D0%B1%D0%BD%D0%BE%D0%B5)**
* **[DEB пакеты (Debian, Ubuntu и тому подобное)](#deb-%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-debian-ubuntu-%D0%B8-%D1%82%D0%BE%D0%BC%D1%83-%D0%BF%D0%BE%D0%B4%D0%BE%D0%B1%D0%BD%D0%BE%D0%B5)**
* **[APT - средство управление пакетами (Debian, Ubuntu и тому подобное)](#apt---%D1%81%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D0%B0%D0%BC%D0%B8-debian-ubuntu-%D0%B8-%D1%82%D0%BE%D0%BC%D1%83-%D0%BF%D0%BE%D0%B4%D0%BE%D0%B1%D0%BD%D0%BE%D0%B5)**
* **[Просмотр содержимого файлов](#%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80-%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B8%D0%BC%D0%BE%D0%B3%D0%BE-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2)**
* **[Манипуляции с текстом](#%D0%9C%D0%B0%D0%BD%D0%B8%D0%BF%D1%83%D0%BB%D1%8F%D1%86%D0%B8%D0%B8-%D1%81-%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%BC)**
* **[Преобразование наборов символов и файловых форматов](#%D0%9F%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BD%D0%B0%D0%B1%D0%BE%D1%80%D0%BE%D0%B2-%D1%81%D0%B8%D0%BC%D0%B2%D0%BE%D0%BB%D0%BE%D0%B2-%D0%B8-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D1%8B%D1%85-%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%BE%D0%B2)**
* **[Форматирование файловых систем](#%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D1%8B%D1%85-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC)**
* **[swap-пространство](#swap-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%BE)**
* **[Создание резервных копий (backup)](#%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D1%80%D0%B5%D0%B7%D0%B5%D1%80%D0%B2%D0%BD%D1%8B%D1%85-%D0%BA%D0%BE%D0%BF%D0%B8%D0%B9-backup)**
* **[DROM](#cdrom)**
* **[Сеть (LAN и WiFi)](#%D0%A1%D0%B5%D1%82%D1%8C-lan-%D0%B8-wifi)**
* **[Microsoft Windows networks(SAMBA)](#microsoft-windows-networkssamba)**
* **[IPTABLES (firewall)](#iptables-firewall)**
* **[Мониторинг и отладка](#%D0%9C%D0%BE%D0%BD%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%BD%D0%B3-%D0%B8-%D0%BE%D1%82%D0%BB%D0%B0%D0%B4%D0%BA%D0%B0)**
* **[Другие полезные команды](#%D0%94%D1%80%D1%83%D0%B3%D0%B8%D0%B5-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B)**


### Системная информация
| Команда                 | Описание      |
|:------------------------|:--------------|
| `arch`                  | отобразить архитектуру компьютера |
| `uname -m`              | отобразить архитектуру компьютера |
| `uname -r`              |  отобразить используемую версию ядра |
| `dmidecode -q`          |	показать аппаратные системные компоненты - ([SMBIOS](http://ru.wikipedia.org/wiki/SMBIOS)/[DMI](http://ru.wikipedia.org/wiki/Direct_Media_Interface)) |
| `hdparm -i /dev/hda`    | вывести характеристики жесткого диска |
| `hdparm -tT /dev/sda`   | протестировать производительность чтения данных с жесткого диска |
| `cat /proc/cpuinfo`     | отобразить информацию о процессоре
| `cat /proc/interrupts`  | показать прерывания |
| `cat /proc/meminfo`     | проверить использование памяти |
| `cat /proc/swaps`       | показать файл(ы) подкачки |
| `cat /proc/version`     | вывести версию ядра |
| `cat /proc/net/dev`     | показать сетевые интерфейсы и статистику по ним |
| `cat /proc/mounts`      | отобразить смонтированные файловые системы |
| `lspci -tv`             | показать в виде дерева [PCI](http://ru.wikipedia.org/wiki/PCI) устройства |
| `lsusb -tv`             | показать в виде дерева [USB](http://ru.wikipedia.org/wiki/USB) устройства |
| `date`                  | вывести системную дату |
| `cal 2007`              | вывести таблицу-календарь 2007-го года |
| `date 041217002007.00`  | установить системные дату и время ММДДЧЧммГГГГ.СС (МесяцДеньЧасМинутыГод.Секунды) |
| `clock -w`              | сохранить системное время в [BIOS](http://ru.wikipedia.org/wiki/BIOS) |

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Остановка системы
| Команда                       | Описание      |
|:------------------------------|:--------------|
| `shutdown -h now`             | Остановить систему |
| `init 0`                      | Остановить систему |
| `telinit 0`                   | Остановить систему |
| `shutdown -h hours:minutes &` | запланировать остановку системы на указанное время |
| `shutdown -c`                 | отменить запланированную по расписанию остановку системы |
| `shutdown -r now`             | перегрузить систему |
| `reboot`                      | перегрузить систему |
| `logout`                      | выйти из системы |

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Файлы и директории
| Команда                 | Описание      |
|:------------------------|:--------------|
| `cd /home` |   перейти в директорию `/home`
| `cd ..` | 	перейти в директорию уровнем выше
| `cd ../..` | 	перейти в директорию двумя уровнями выше
| `cd` | 	перейти в домашнюю директорию
| `cd ~user` | 	перейти в домашнюю директорию пользователя user
| `cd -` | 	перейти в директорию, в которой находились до перехода в текущую директорию
| `pwd` | 	показать текущюю директорию
| `ls` | 	отобразить содержимое текущей директории
| `ls -F` | 	отобразить содержимое текущей директории с добавлением к именам символов, храктеризующих тип
| `ls -l` | 	показать детализированое представление файлов и директорий в текущей директории
| `ls -a` | 	показать скрытые файлы и директории в текущей директории
| `ls *[0-9]*` | 	показать файлы и директории содержащие в имени цифры
| `tree` | 	показать дерево файлов и директорий, начиная от корня (`/`)
| `lstree` | показать дерево файлов и директорий, начиная от корня (`/`)
| `mkdir dir1` | 	создать директорию с именем `dir1`
| `mkdir dir1 dir2` | 	создать две директории одновременно
| `mkdir -p /tmp/dir1/dir2` | 	создать дерево директорий
| `rm -f file1` | 	удалить файл с именем `file1`
| `rmdir dir1` | 	удалить директорию с именем `dir1`
| `rm -rf dir1` | 	удалить директорию с именем `dir1` и рекурсивно всё её содержимое
| `rm -rf dir1 dir2` | 	удалить две директории и рекурсивно их содержимое
| `mv dir1 new_dir` | 	переименовать или переместить файл или директорию
| `cp file1 file2` | 	сопировать файл `file1` в файл `file2`
| `cp dir/* .` | 	копировать все файлы директории dir в текущую директорию
| `cp -a /tmp/dir1 .` | 	копировать директорию `dir1` со всем содержимым в текущую директорию
| `cp -a dir1 dir2` | 	копировать директорию `dir1` в директорию `dir2`
| `ln -s file1 lnk1` | 	создать символическую ссылку на файл или директорию
| `ln file1 lnk1` | 	создать "жёсткую" (физическую) ссылку на файл или директорию
| `touch -t 0712250000 fileditest` | 	модифицировать дату и время создания файла, при его отсутствии, создать файл с указанными датой и временем (YYMMDDhhmm) 

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Поиск файлов
| Команда                 | Описание      |
|:------------------------|:--------------|
| `find / -name file1` | найти файлы и директории с именем `file1`. Поиск начать с корня (`/`)
| `find / -user user1` |	найти файл и директорию принадлежащие пользователю user1. Поиск начать с корня (`/`)
| `find /home/user1 -name "*.bin"` |	Найти все файлы и директории, имена которых оканчиваются на `.bin`. Поиск начать с `/ home/user1`
| `find /usr/bin -type f -atime +100` |	найти все файлы в `/usr/bin`, время последнего обращения к которым более 100 дней
| `find /usr/bin -type f -mtime -10` |	найти все файлы в `/usr/bin`, созданные или изменённые в течении последних 10 дней
| `find / -name *.rpm -exec chmod 755 '{}' \;` |	найти все фалы и директории, имена которых оканчиваются на `.rpm`, и изменить права доступа к ним
| `find / -xdev -name "*.rpm"` |	найти все фалы и директории, имена которых оканчиваются на `.rpm`, игнорируя съёмные носители, такие как cdrom, floppy и т.п.
| `locate "*.ps"` |	найти все файлы, сожержащие в имени `.ps`. Предварительно рекомендуется выполнить команду `updatedb`
| `whereis halt` |	показывает размещение бинарных файлов, исходных кодов и руководств, относящихся к файлу `halt`
| `which halt` |	отображает полный путь к файлу `halt` 

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Монтирование файловых систем
| Команда                 | Описание      |
|:------------------------|:--------------|
| `mount /dev/hda2 /mnt/hda2` |  монтирует раздел `hda2` в точку монтирования `/mnt/hda2`. Убедитесь в наличии директории-точки монтирования `/mnt/hda2`
| `umount /dev/hda2` |	размонтирует раздел `hda2`. Перед выполнением, покиньте `/mnt/hda2`
| `fuser -km /mnt/hda2` |	принудительное размонтирование раздела. Применяется в случае, когда раздел занят каким-либо пользователем
| `umount -n /mnt/hda2` |	выполнить размонитрование без занесения информации в `/etc/mtab`. Полезно когда файл имеет атрибуты "только чтение" или недостаточно места на диске
| `mount /dev/fd0 /mnt/floppy` |	монтировать флоппи-диск
| `mount /dev/cdrom /mnt/cdrom` |	монтировать CD или DVD
| `mount /dev/hdc /mnt/cdrecorder` |	монтировать CD-R/CD-RW или DVD-R/DVD-RW(+-)
| `mount -o loop file.iso /mnt/cdrom` |	смонтировать ISO-образ
| `mount -t vfat /dev/hda5 /mnt/hda5` |	монтировать файловую систему [Windows FAT32](http://ru.wikipedia.org/wiki/FAT32)
| `mount -o bind /home/user/prg /var/ftp/user` |	"монтирует" директорию в директорию (`binding`). Доступна с версии ядра 2.4.0. Полезна, например, для предоставления содержимого пользовательской директории через [ftp](http://ru.wikipedia.org/wiki/Ftp) при работе ftp-сервера в "песочнице" (`chroot`), когда симлинки сделать невозможно.

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Дисковое пространство
* `df -h` - отображает информацию о смонтированных разделах с отображением общего, доступного и используемого пространства (Прим.переводчика. ключ `-h` работает не во всех *nix системах)
* `ls -lSr | more` - выдаёт список файлов и директорий рекурсивно с сортировкой по возрастанию размера и позволяет осуществлять постраничный просмотр
* `du -sh dir1` - подсчитывает и выводит размер, занимаемый директорией `dir1` (Прим.переводчика. ключ `-h` работает не во всех *nix системах)
* `du -sk *|sort -rn` - отображает размер и имена файлов и директорий, с соритровкой по размеру
* `rpm -q -a --qf '%10{SIZE}\t%{NAME}\n' | sort -k1,1n` - показывает размер используемого дискового пространства, занимаемое файлами rpm-пакета, с сортировкой по размеру (fedora, redhat и т.п.)
* `dpkg-query -W -f='${Installed-Size;10}\t${Package}\n' | sort -k1,1n` - показывает размер используемого дискового пространства, занимаемое файлами deb-пакета, с сортировкой по размеру (ubuntu, debian т.п.) 

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Пользователи и группы
| Команда                 | Описание      |
|:------------------------|:--------------|
| `groupadd group_name` | создать новую группу с именем group_name
| `groupdel group_name` |	удалить группу `group_name`
| `groupmod -n new_group_name old_group_name` |	переименовать группу `old_group_name` в `new_group_name`
| `useradd user1` |	создать пользователя `user1`
| `userdel -r user1` |	удалить пользователя user1 и его домашний каталог
| `passwd` |	сменить пароль
| `passwd user1` |	сменить пароль пользователя user1 (только root)
| `chage -E 2005-12-31 user1` |	установить дату окончания действия учётной записи пользователя user1
| `pwck` |	проверить корректность системных файлов учётных записей. Проверяются файлы `/etc/passwd` и `/etc/shadow`
| `grpck` |	проверяет корректность системных файлов учётных записей. Проверяется файл `/etc/group`
| `newgrp [-] group_name` |	изменяет первичную группу текущего пользователя. Если указать "`-`", ситуация будет идентичной той, в которой пользователь вышил из системы и снова вошёл. Если не указывать группу, первичная группа будет назначена из `/etc/passwd` 

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Выставление/изменение полномочий на файлы
| Команда                 | Описание      |
|:------------------------|:--------------|
| `ls -lh` |   просмотр полномочий на файлы и директории в текущей директории
| `chmod ugo+rwx directory1` | 	добавить полномочия на директорию `directory1` ugo(User Group Other)+rwx(Read Write eXecute) - всем полные права. Аналогичное можно сделать таким образом `chmod 777 directory1`
| `chmod go-rwx directory1` | 	отобрать у группы и всех остальных все полномочия на директорию `directory1`.
| `chown user1 file1` | 	назначить владельцем файла `file1` пользователя user1
| `chown -R user1 directory1` | 	назначить рекурсивно владельцем директории directory1 пользователя `user1`
| `chgrp group1 file1` | 	сменить группу-владельца файла `file1` на group1
| `chown user1:group1 file1` | 	сменить владельца и группу владельца файла `file1`
| `find / -perm -u+s` | 	найти, начиная от корня, все файлы с выставленным SUID
| `chmod u+s /bin/binary_file` | 	назначить SUID-бит файлу `/bin/binary_file`. Это даёт возможность любому пользователю запускать на выполнение файл с полномочиями владельца файла.
| `chmod u-s /bin/binary_file` | 	снять SUID-бит с файла `/bin/binary_file`.
| `chmod g+s /home/public` | 	назначить SGID-бит директории `/home/public`.
| `chmod g-s /home/public` | 	снять SGID-бит с директории `/home/public`.
| `chmod o+t /home/public` | 	назначить STIKY-бит директории `/home/public`. Позволяет удалять файлы только владельцам
| `chmod o-t /home/public` | 	снять STIKY-бит с директории `/home/public` 

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Специальные атрибуты файлов
| Команда                 | Описание      |
|:------------------------|:--------------|
| `hattr +a file1` | позволить открывать файл на запись только в режиме добавления
| `hattr +c file1` |	позволяет ядру автоматически сжимать/разжимать содержимое файла.
| `hattr +d file1` |	указавет утилите dump игнорировать данный файл во время выполнения backup'а
| `hattr +i file1` |	делает файл недоступным для любых изменений: редактирование, удаление, перемещение, создание линков на него.
| `hattr +s file1` |	позволяет сделать удаление файла безопасным, т.е. выставленный атрибут s говорит о том, что при удалении файла, место, занимаемое файлом на диске заполняется нулями, что предотвращяет возможность восстановления данных.
| `hattr +S file1` |	указывает, что, при сохранении изменений, будет произведена синхронизация, как при выполнении команды sync
| `hattr +u file1` |	данный атрибут указывает, что при удалении файла содержимое его будет сохранено и при необходимости пользователь сможет его восстановить
| `sattr` |	показать атрибуты файлов 

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Архивирование и сжатие файлов
| Команда                 | Описание      |
|:------------------------|:--------------|
| `bunzip2 file1.bz2` | разжимает файл `file1.gz`
| `gunzip file1.gz` |
| `gzip file1` | сжимает файл `file1`
| `bzip2 file1` | сжимает файл `file1`
| `gzip -9 file1` | сжать файл `file1` с максимальным сжатием
| `rar a file1.rar test_file` | создать rar-архив `file1.rar` и включить в него файл `test_file`
| `rar a file1.rar file1 file2 dir1` | создать rar-архив `file1.rar` и включить в него `file1`, `file2` и `dir1`
| `unrar x file1.rar` | распаковать rar-архив
| `tar -cvf archive.tar file1` | создать tar-архив `archive.tar`, содержащий файл `file1`
| `tar -cvf archive.tar file1 file2 dir1` | создать tar-архив `archive.tar`, содержащий файл `file1`, `file2` и `dir1`
| `tar -tf archive.tar` | показать содержимое архива
| `tar -xvf archive.tar` | распаковать архив
| `tar -xvf archive.tar -C /tmp` | распаковать архив в `/tmp`
| `tar -cvfj archive.tar.bz2 dir1` | создать архив и сжать его с помощью bzip2(Прим.переводчика. ключ `-j` работает не во всех *nix системах)
| `tar -xvfj archive.tar.bz2` | разжать архив и распаковать его(Прим.переводчика. ключ `-j` работает не во всех *nix системах)
| `tar -cvfz archive.tar.gz dir1` | создать архив и сжать его с помощью gzip
| `tar -xvfz archive.tar.gz` | разжать архив и распаковать его
| `zip file1.zip file1` | создать сжатый zip-архив
| `zip -r file1.zip file1 file2 dir1` | создать сжатый zip-архив и со включением в него нескольких файлов и/или директорий
| `unzip file1.zip` | разжать и распаковать zip-архив 

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### [RPM](http://ru.wikipedia.org/wiki/RPM) пакеты ([Fedora](http://ru.wikipedia.org/wiki/Fedora), [Red Hat](http://ru.wikipedia.org/wiki/Red_Hat) и тому подобное)
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### [YUM](http://ru.wikipedia.org/wiki/Yum) - средство обновления пакетов ([Fedora](http://ru.wikipedia.org/wiki/Fedora), [RedHat](http://ru.wikipedia.org/wiki/Red_Hat) и тому подобное)
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### [DEB](http://ru.wikipedia.org/wiki/DEB) пакеты ([Debian](http://ru.wikipedia.org/wiki/Debian), [Ubuntu](http://ru.wikipedia.org/wiki/Ubuntu) и тому подобное)
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### [APT](http://ru.wikipedia.org/wiki/APT) - средство управление пакетами ([Debian](http://ru.wikipedia.org/wiki/Debian), [Ubuntu](http://ru.wikipedia.org/wiki/Ubuntu) и тому подобное)
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Просмотр содержимого файлов
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Манипуляции с текстом
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Преобразование наборов символов и файловых форматов
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Анализ файловых систем
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Форматирование файловых систем
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### swap-пространство 
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Создание резервных копий (backup)
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### CDROM
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Сеть (LAN и WiFi)
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Microsoft Windows networks([SAMBA](http://ru.wikipedia.org/wiki/Samba)) 
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### IPTABLES ([firewall](http://ru.wikipedia.org/wiki/Firewall))
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Мониторинг и отладка
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


### Другие полезные команды
| Команда                 | Описание      |
|:------------------------|:--------------|
TODO

[к началу](#%D0%9E%D1%87%D0%B5%D0%BD%D1%8C-%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-linux-%D0%BD%D0%B0-%D0%BE%D0%B4%D0%BD%D0%BE%D0%BC-%D0%BB%D0%B8%D1%81%D1%82%D0%B5)


**[Оригинал](http://www.f-notes.info/linux:linux_command)**

















