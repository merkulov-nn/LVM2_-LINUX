# LVM2_-LINUX
Домашнее задание

Работа с LVM

Описание/Пошаговая инструкция выполнения домашнего задания:

Для выполнения домашнего задания используйте методичку

Работа с LVM https://drive.google.com/file/d/1DMxzJ6ctD0-I0My-iJJEGaeLDnIs13zj/view?usp=share_link

Что нужно сделать?

на имеющемся образе (centos/7 1804.2)
https://gitlab.com/otus_linux/stands-03-lvm
/dev/mapper/VolGroup00-LogVol00 38G 738M 37G 2% /

уменьшить том под / до 8G

выделить том под /home

выделить том под /var (/var - сделать в mirror)

для /home - сделать том для снэпшотов

прописать монтирование в fstab (попробовать с разными опциями и разными файловыми системами на выбор)

Работа со снапшотами:

сгенерировать файлы в /home/

снять снэпшот

удалить часть файлов

восстановиться со снэпшота

(залоггировать работу можно утилитой script, скриншотами и т.п.)
