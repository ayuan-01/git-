# 使用流程

1. 初始化仓库

   ```git
   git init
   ```

   这将创建一个隐藏的 `.git` 文件夹，Git 会在其中存储版本控制信息。

2. 克隆远程仓库

   ```git
   git clone https://github.com/user/repo.git
   ```

3. 检查状态，添加文件到暂存区（将所有修改添加），提交更改

   ```git
   git add <文件名>
   git add .
   git commit -m "提交信息"
   ```

4. 查看提交历史

   ```git
   git log
   ```

5. 推送到远程仓库

   - 添加远程仓库的连接
   - 查看当前连接的远程仓库
   - 拉取远程仓库的更新
   - 将本地文件添加到仓库中
   - 将本地修改推送到远程仓库

   ```git
   git remote add origin https://github.com/ayuan-01/git-note
   git remote -v
   git pull origin <分支名>
   git add .
   git commit -m "Initial commit"
   git push origin main(分支名)
   
   ```

   

6. 分支

   - 创建新分支
   - 切换分支
   - 合并分支

   ```git
   git branch <分支名>
   git checkout <分支名>
   git merge <分支名>
   ```

   - 查看当前分支

     ```git
     git branch
     可以使用命令查看更加详细的分支信息，包括远程和本地分支
     git branch -a
     ```

     