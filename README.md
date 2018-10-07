### 电商网站开发实践

#### git初始化

``` bash
$ touch .gitignore
$ vim .gitignore

$ git init
$ git status
$ git add .
$ git commit -am 'first commit init project'
$ git remote add neworigin https://github.com/ThomasLeedev/tommall.git
$ git push -u neworigin master
$ git branch -r
  neworigin/master

$ git checkout -b v1.0 neworigin/master
Switched to a new branch 'v1.0'
Branch 'v1.0' set up to track remote branch 'master' from 'neworigin'.

$ git push neworigin HEAD -u
$ git branch
  master
* v1.0

```