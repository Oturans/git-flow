# Git-Flow
Тестовый репозиторий для отработки инструмента Git-Flow

[Туториал от атласиан](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

---
Предварительно репозиторий создаем на Github:
[https://github.com/Oturans/git-flow](https://github.com/Oturans/git-flow)

После чего делаем клон на комп:

```
git clone git@github.com:Oturans/git-flow.git

```

Выполненные команды:

```
git flow init

git branch develop

git push -u origin develop

git flow feature start feature_branch

git flow feature finish feature_branch

git flow release start 0.1.0

git flow release finish '0.1.0'

git flow hotfix start hotfix_branch

git flow hotfix finish hotfix_branch

git push --all
```

---

Правила Git-Flow (Запомнить!):

1. A develop branch is created from master
2. A release branch is created from develop
3. Feature branches are created from develop
4. When a feature is complete it is merged into the develop branch
5. When the release branch is done it is merged into develop and master
6. If an issue in master is detected a hotfix branch is created from master
7. Once the hotfix is complete it is merged to both develop and master

