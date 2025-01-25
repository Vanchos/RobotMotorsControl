# RobotMotorsControl
Учебный проект Skillbox

## 1. Создание проекта в GitHub и клонирование на компьютер
**Шаг 1.** Настройка локального репозитория
 
`git config --global user.name "Vanchos"`

`git config --global user.email ivan.ivanov@mail.ru`

`git config --global core.editor nano`


**Шаг 2.** Создание репозитория RobotMotorsControl на GitHub и клонирование на локальный компьютер

`git clone https://github.com/Vanchos/RobotMotorsControl.git`  
Cloning into 'RobotMotorsControl'...  
remote: Enumerating objects: 3, done.  
remote: Counting objects: 100% (3/3), done.  
remote: Compressing objects: 100% (2/2), done.  
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)  
Unpacking objects: 100% (3/3), 906 bytes | 906.00 KiB/s, done.  

`cd RobotMotorsControl`

`git push`  
Username for 'https://github.com': Vanchos  
Password for 'https://Vanchos@github.com':   
Enumerating objects: 5, done.  
Counting objects: 100% (5/5), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (2/2), done.  
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0)  
To https://github.com/Vanchos/RobotMotorsControl.git  
   ad1d17b..788a621  main -> main  

**Шаг 3** Создание токена и настройка авторизации с локального компьютера

`git remote set-url origin https://Vanchos:github_pat_???????????????????????????????????????????????@github.com/Vanchos/RobotMotorsControl.git`

## 2. Создание файлов в каталоге репозитория и сохранение изменений в репозитории

`nano motors_control.py`

`git add motors_control.py`

`git commit -m "Add new file motors_control.py"`  
[main dc2aa4d] Add new file motors_control.py  
 1 file changed, 33 insertions(+)  
 create mode 100644 motors_control.py  

`git push`  
Enumerating objects: 7, done.  
Counting objects: 100% (7/7), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (5/5), done.  
Writing objects: 100% (5/5), 802 bytes | 802.00 KiB/s, done.  
Total 5 (delta 0), reused 0 (delta 0)  
To https://github.com/Vanchos/RobotMotorsControl.git  
   02b5189..e421fbf  main -> main  



