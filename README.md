# linux
linux commands and scripts

create file "console" for use commands in linux, and automation routin work
# kill all by name
# поменять кодировку файла на UTF-8 например и создать новый файл
# tar/zip/gzip - archive, unachive
# узнать свой публичный ip
# curl ifconfig.co

# внутренний ip
# hostname -I

# fast chmod
# sudo chmod -R 777 ./

# ls
#ls -lAhXgF --color

# поиск процесов по имени, можно добавить сюда сколько процесорного времени и места в памяти занимают
#ps -eo user,pid,comm,cmd | grep "$1"

# кол во строк в файле
# wc

# grep some_text


BASH
# Before use execute this command in bash:
# chmod +x jarvis


# Как для судо добавить пароль что бы он был по умолчанию
# echo "$root" | sudo command

# Вывод команды в переменную mydir=`pwd`
#                            mydir=$(pwd)
# Математические команды var1=$(( 5 + 5 ))
# if pwd  # если команда выполнится успешно и вернет 0 то условие выполниться иначе блок else
#then
#команды
#else
#команды
#fi
# сравнение чисел [ $1 -gt 5 ]
# сравнение строк [ $1 \> "hello" ]
# сравнение строк [ $1 \> "hello" ]
# -n str1 не пустая строка
# -z str1 пустая строка

#-d fileПроверяет, существует ли файл, и является ли он директорией.
#-e fileПроверяет, существует ли файл.
#-f file Проверяет, существует ли файл, и является ли он файлом.
#-r fileПроверяет, существует ли файл, и доступен ли он для чтения.
#-s file Проверяет, существует ли файл, и не является ли он пустым.
#-w fileПроверяет, существует ли файл, и доступен ли он для записи.
#-x fileПроверяет, существует ли файл, и является ли он исполняемым.
#file1 -nt file2 Проверяет, новее ли file1, чем file2.
#file1 -ot file2Проверяет, старше ли file1, чем file2.
#-O file Проверяет, существует ли файл, и является ли его владельцем текущий пользователь.
#-G fileПроверяет, существует ли файл, и соответствует ли его идентификатор группы идентификатору группы текущего пользователя.
#https://habr.com/ru/company/ruvds/blog/325928/

#Проверка параметров
#!/bin/bash
#if [ -n "$1" ]
#then
#echo Hello $1.
#else
#echo "No parameters found. "
#fi
