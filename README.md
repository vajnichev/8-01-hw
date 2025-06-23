# # Домашнее задание к занятию "`Git`" - `Важничев Георгий`






## Задание 1



**Что нужно сделать:**



1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).More actions

2. Создайте  **новый отдельный публичный репозиторий**. Обязательно поставьте галочку в поле «Initialize this repository with a README».
3. Склонируйте репозиторий, используя https протокол `git clone ...`.
4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.
6. Выполните команду `git status` и запомните результат.
7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.
9. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.
10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.
11. Ещё раз выполните команды `git diff` и `git diff --staged`.
12. Теперь можно сделать коммит `git commit -m 'First commit'`.
13. Сделайте `git push origin master`.



В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

**Решение**




## Решение 1



1-6

georgiy@georgiy-vajnichev:~/8-01-hw$ cd ~/8-01-hw

georgiy@georgiy-vajnichev:~/8-01-hw$ git init

georgiy@georgiy-vajnichev:~/8-01-hw$  git config --global user.name GeorgiyVajnichev

georgiy@georgiy-vajnichev:~/8-01-hw$  git config --global user.email vajnichev@gmail.com



![статус до коммита](https://github.com/vajnichev/8-01-hw/blob/master/img/8.1.2.png)

7-11
добавим отслеживание

<img src = "img/8.1.2.png" width = 100%>

![добавим отслеживание](https://github.com/vajnichev/8-01-hw/blob/master/img/8.1.3.png)

Коммит после решения  



[ссылка](https://github.com/vajnichev/8-01-hw/blob/master/README.md?plain=1)


###Задание 2

Что нужно сделать:

    Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
    Добавьте файл .gitignore в следующий коммит git add....
    Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
    Сделайте коммит и пуш.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.


## Решение 2

1-2.

<img src = "img/8.1.4.png" width = 100%>

3.

<img src = "img/8.1.5.png" width = 100%>

4.


<img src = "img/8.1.6.png" width = 100%>

Коммит после решения 

[ссылка](https://github.com/vajnichev/8-01-hw/blob/master/README.md?plain=1)

