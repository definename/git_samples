# GIT samples 
## GIT samples 
###### GIT samples 

# Master changes were made
# Hotfix changes were added
# Hotfix2 changes were added
# Here is message to resolve conflict
# Here is patch message
## Here is one more patch message
Here is one more commit to test interactive rebase


:seedling: In order to delete branch on git server side we need to performe this command:
```
git push origin --delete branchname
```

:seedling: To figure out this error: `fatal: refusing to merge unrelated histories` we need to do the following:
```
git merge submaster --allow-unrelated-histories
```

:seedling: Ancestor reference. Difference bitween `HEAD^` and `HEAD~`

Символ `^` и `~` в конце ссылки с точки зрения Git соответствует предку коммита. После этих символов можно указать число: `HEAD^2` которое будет указывать номер предка. Разница между ними заключается только в том что синтаксис `HEAD^2` применяется только с коммитани слияния.
`HEAD^3` эквивалентно `HEAD^^^`. Указанные обозначения можно комбинировать `HEAD~3^2`

:seedling: Set custom core editor

- VSCode `git config --global core.editor "code --wait"`

:seedling: Configure `graph` alias
```git config --global alias.graph  "log --oneline --graph --all --decorate"```

:seedling: Git log show midified files only:
```git log --stat -1```
```git log --name-status -1```
```git log --name-only -1```


