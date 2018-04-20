# test2
第二次测试

git命令
1.克隆代码
git clone url
2.创建分支
git checkout -b 分支名
3.查看所有分支
git branch
4.删除分支名
git branch -D 分支名
5.提交本地分支到远程分支上
git push origin 分支名
6.设置全局变量
git config --global user.email '邮箱'
git config --global user.name '注册名'
7.合并add和commit操作
git commit -am ''
8.创建秘钥
ssh-keygen -t rsa -C 账号
9.下拉远程自己分支代码到本地代码中
git pull origin 分支名
10.比较分支之间的不同
git diff 分支1 分支2
11.合并分支
git merge 分支
12.打tag标签
git tag -a 版本号 -m 注释
13.推送版本
git push origin 版本号
14.删除远程分支
git push origin --delete 分支名
15.查看版本号
git tag
16.删除远程版本号
git push origin --delete tag 版本号
17.删除版本号
git tag -d 版本号
18.缓存本地修改的代码
git stash
19.查看缓存的片段
git stash list
20.还原缓存的代码
git stash apply stash{x}
21.返回代码
git reset --hard xxxx
22.查看历史
git log
23.查看状态
git status
24.初始化仓库
git init
