# Команды и инструкция по работе с GIT.

## Шрифты 

 *курсив.* 

 **жирный.**

 ~~зачёркнутый~~

 Также имеются дополнительные варианты выделения _курсивом_ и __жирным__ с помощью нижних подчёркиваний.(одно подчёркивание - курсив, два подчёркивания - жирный) Это нужно для того чтобы выделять сразу двумя способами _**и жирным и курсивом**_ 


1) git init - инициализирует локальный репозиторий

2) git status - показывает состояние репозитория 

3) git log - показывает все коммиты 

4) git add .\file_name - отслеживает изменения файла 

5) git checkout 7ed6 - переход к определенному комиту

6) git checkot master - переход к главному комиту

7) git commit -a -m  - добавляет все файлы в отслеживаемые и создаёт комит с сообщением 

8) git dff - показывает разницу между текущим фалом и предыдущим комитом

9) git branch - показывает все ветки 

10) git branch branch_name - создаёт новую ветку с именем branch_name

11) git checkout branch_name - переход на ветку с именем branch_name

12) git merge branch_name - слияние ветки branch_name с веткой в которой сейчас находимся 

13) git -d branch_name - удаление ветки с именем branch_name 

14) git log --graph - список всех комиитов в веток 

15) git push - загрузка на github и тд

16) git pull - выгрузка

17) git clone - создаёт копию репозитория с git 
 
 # Инструкция по работе с Git
 
 Для работы с GIT нужно его инициализировать в терминале с помощью команды 
 * git init

Чтобы GIT мог работать с файлом нужно добавить этот файл в отслеживаемые с помощью команды
 * git add

!!Обязательно сохранять файл перед добавлением!!

 * ctrl+s

Комит создаётся командой
 * git commit


end




