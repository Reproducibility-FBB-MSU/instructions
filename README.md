# Инструкции для проекта "Reproducibility"

В этой папке лежат инструкции для студентов. 

## Описание проекта

Цель проекта -- обучить Python в биоинформатике через воспроизведение результатов статей. 

## GitHub инструкции

Полный вариант инструкций по GitHub можно найти тут: https://github.com/homo-sapiens34/Python_FBB_2017/blob/master/git-cookbook.md

1. Зарегистрируйтесь на GitHub. Перейдите на страницу организации [Reproducibility organisation](https://github.com/Reproducibility-FBB-MSU) и добавьтесь в нее (или же напишите одному из преподавателей свой никнейм на сайте). Скорее всего, придется подождать ответ 

2. Установите git у себя на локальном компьютере. Например, с помощью conda: 

```
conda install git
```

3. Создайте пустую папку. Клонируйте ваш проект в эту папку (clone). Например: 

```git clone https://github.com/Reproducibility-FBB-MSU/instructions.git```

4. Зайдите в созданную директорию с проектом. Сделайте первый коммит.
Например, добавьте свое имя в README.md. Используйте [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Сохраните изменения. Добавтье файл, сделайте коммит и push:

```
git add README.md
git commit -m "Student's introduction"
git push
```

## TODO list for instructors

1. Add more thorough walkthrough for students (e.g. addition of ssh key).

2. Add policy description (code should be commented and readable, etc.)
