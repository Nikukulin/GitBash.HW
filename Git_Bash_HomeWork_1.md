# Git Bash. HomeWork_1


### Посмотреть где я
```bash
	== pwd
```
### Создать папку
```bash
	== mkdir folder_1
```
### Зайти в папку
```bash
	== cd folder_1
```
### Создать 3 папки
```bash
	== mkdir fol_1 fol_2 fol_3
```
### Зайти в любую папку
```bash
	== cd fol_1
```
### Создать 5 файлов (3 txt, 2 json)
```bash
	== touch t_1.txt t_2.txt t_3.txt j_1.json j_2.json
```
### Создать 3 папки
```bash
	== mkdir papka_1 papka_2 papka_3
```
### Вывести список содержимого папки
```bash
	== ls folder_1 (ls; ls -la)
```
### + Открыть любой txt файл
```bash
	== vim t_1.txt
```
### + написать туда что-нибудь, любой текст
```bash
	== i (INSERT) I have two cute cats
```
### + сохранить и выйти
```bash
	== esc :wq
```
### Выйти из папки на уровень выше
```bash
	== cd ..
```
### Переместить любые 2 файла, которые вы создали, в любую другую папку
```bash
	== mv t_1.txt t_2.txt papka_1/
```
### Скопировать любые 2 файла, которые вы создали, в любую другую папку
```bash
	== cp papka_1/t_1.txt t_2.txt ../fol_1
```
### Найти файл по имени
```bash
	== find . -iname “t_1*”
```
### Просмотреть содержимое в реальном времени (команда grep) изучите как она работает
```bash
	== tail -f t_1.txt
```
### Вывести несколько первых строк из текстового файла
```bash
	== head -n 3 t_1.txt
```
### Вывести несколько последних строк из текстового файла
```bash
	== tail -n 3 t_1.txt
```
### Просмотреть содержимое длинного файла (команда less) изучите как она работает
```bash
	== less t_1.txt
```
### Вывести дату и время
```bash
	== date
```

# http запрос
```bash
== curl http://162.55.220.72:5005/terminal-hw-request
== curl "http://162.55.220.72:5005/get_method?name='Kolya'&age=25"
```
# Скрипт
```bash
== touch myscript.txt
== vim myscript.txt


#!/bin/bash
cd dir_3;
mkdir nik_1 nik_2 nik_3;
cd nik_2;
touch lam_1.txt lam_2.txt lam_3.txt lam_4.json lam_5.txt;
mkdir pap_1 pap_2 pap_3;
mv lam_1.txt lam_2.txt nik_1;
ls -la


== chmod +x ./myscript.txt
== ./myscript.txt
```