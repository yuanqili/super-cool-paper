对于新项目而言

1. Github 上创建新的 repository
2. 本地编写代码
3. `git init` – 本地初始化 git 仓库
4. `git add .` – 添加所有文件到暂存区
5. `git commit -m "first commit"` – 提交暂存区的代码到本地仓库
6. `git branch -M main` – 重命名分支为 main
7. `git remote add origin <url>` – 添加远程仓库地址
8. `git push -u origin main` – 推送本地仓库的代码到远程仓库

后续当代码修改过后

1. `git add .` – 添加所有文件到暂存区
2. `git commit -m "commit message"` – 提交暂存区的代码到本地仓库
3. `git push` – 推送本地仓库的代码到远程仓库
