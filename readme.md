Каралкин Максим Алексеевич КИ-17-06б
Каралкин Максим Алексеевич КИ-17-06б
Скопировал репоситорий используя git clone. 
Добавил все файлы в свой репозиторий с комментарием clone-repo. 
Выполнил команды : 
  $ git filter-branch --tree-filter 'rm -f images/*.jpg' HEAD 
  $ git filter-branch -f --tree-filter 'rm -rf folder1' HEAD
  $ git filter-branch --tree-filter 'rm -rf *копия*' HEAD
  $ git reflog expire --expire=now --all && git gc --prune=now --aggressive 
  $ git push origin --force --all 
  $ git push origin --force --tags 
  $ git push
