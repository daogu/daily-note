## 目标：创建新项目 ##

1. 新建文件夹

   `mkdir something`

2. 根目录执行

    `git init`

3. 配置当前项目的git用户信息：

   `git config user.name "user"`

   `git config user.email "email"`

4. 创建README.md，编辑相关内容

   `vim README.md`

5. 登录github，创建对应新的repositories

6. 关联到对应的repositories

   `git remote add origin 仓库地址` 

7. 添加新增文件，提交到head，推送到远程仓库

   `git add ./*`

   `git commit -m '提交信息'`

   `git push origin master`

