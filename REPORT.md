<!-- report name -->
# Devtools report lab-2

## Task 1

Запустите локальный веб-визуализатор репозитория и сделайте так, чтобы в нём отображалось нормальное описание репозитория.

![image](docs/2.png)


## Task 2

Перенесите все коммиты, находящиеся в ветке ci, в ветку master с объединением всех коммитов в один и изменением сообщения таким образом, чтобы оно полностью описывало все вносимые изменения. Удалите ветку ci

<!-- code -->
```bash
git checkout ci
git rebase -i HEAD~2
git checkout master
git cherry-pick ci
git checkout master
git branch -D ci
```

![image](docs/2.png)


## Task 3

`git reflog`

`git checkout aca3abb`
`git branch old-master`

![image](docs/3,1.png)
![image](docs/3,2.png)
