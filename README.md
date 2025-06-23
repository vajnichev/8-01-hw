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

