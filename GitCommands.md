# Команды Git
`git clone <url>` – создать локальную копию удалённого репозитория.
`git status` – показывает текущие изменения, отслеживаемые и не отслеживаемые файлы.

`git add .` – добавить все изменения в **staging area** (можно точечно: `git add file.txt`).
`git branch` – список всех локальных веток (звёздочка = текущая).
`git branch bug-fix` – создать новую ветку **bug-fix**.
`git commit -m "Сообщение"` – зафиксировать изменения с комментарием.
`git push origin bug-fix` – отправить ветку **bug-fix** на GitHub.
`git pull origin bug-fix` – подтянуть изменения из ветки c GitHub.
`git merge bug-fix` – слить ветку **bug-fix** в текущую ветку.