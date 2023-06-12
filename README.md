# Git-Bash
# HOMEWORK 1
## _Linux terminal commands (Git Bash)_
## _Задание 1_
| TASK | SOLUTION |
| ------ | ------ |
| 1 Посмотреть где я | pwd |
| 2 Cоздать папку | mkdir hw1 |
| 3 Зайти в папку | cd hw1 |
| 4 Создать 3 папки | mkdir hw2 hw3 hw4 |
| 5 Зайти в любоую папку | cd hw2 |
| 6 Создать 5 файлов (3 txt, 2 json) | touch file1.txt file2.txt file3.txt file4.json file5.json |
| 7 Создать 3 папки | mkdir hw5 hw6 hw7 |
| 8 Вывести список содержимого папки  | ls -la |
| 9 Открыть любой txt файл | vim file1.txt |
| 10 Написать туда что-нибудь, любой текст. | {"name":"Sergey"} |
| 11 сохранить и выйти. | esc :wq |
| 12 Выйти из папки на уровень выше | cd .. |
| 13 переместить любые 2 файла, которые вы создали, в любую другую папку. | mv file1.txt file2.txt hw6/ |
| 14 скопировать любые 2 файла, которые вы создали, в любую другую папку. | cp file4.json file5.json hw6/ |
| 15 Найти файл по имени | find . -name "file1.txt" |
| 16 просмотреть содержимое в реальном времени (команда grep) изучите как она работает. | grep "" file1.txt |
| 17 вывести несколько первых строк из текстового файла | head file1.txt -n 3 |
| 18 вывести несколько последних строк из текстового файла | tail file1.txt -n 3 |
| 19 просмотреть содержимое длинного файла (команда less) изучите как она работает. | less file1.txt |
| 20 вывести дату и время   | date или date + "%A %d %B" (полное наименование дня/месяца) |

## _Задание 2_
***Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request***
```sh
curl http://162.55.220.72:5005/terminal-hw-request
```
## _Задание 3_
***Написать скрипт, который автоматически выполнит пункты (3, 4, 5, 6, 7, 8, 13) из Задания 1***

```sh
vim script
#!/bin/bash
cd hw1
mkdir hw2 hw3 hw4
cd hw2
touch file1.txt file2.txt file3.txt file4.json file5.json
mkdir hw5 hw6 hw7
ls -la
mv file1.txt file2.txt hw6/
esq: wq
./script
