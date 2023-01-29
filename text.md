这种文件叫markdown 自己搜语法 做笔记时可能会用

git 语法

1. git 下载插件 已完成
2. git 注册
3. git init
   git remote origin /仓库

   git config user.email
   git config user.name
----------------------------------------------------

1. 开发写代码 git add .  .代表保存所有到本地， 可多次
2. git commit -m '一段文字'  把本地的当前保存的内容进行本地提交
3. 目前 本地环境下 开发内容保存完成
4. git pull origin [分支名] 拉取远端最新代码 -- 单人开发不需要
5. git push origin [分支名] 推到github、或者是其他仓库
   切仓库 切之前必须让当前分支没有改动
   git branch [分支名] 创建分支
   git checkout [分支名] 切换分支
   git merge [分支名]
 -----------------------------------------------------
1. git log 查看日志
2. git reset [commit 值] 回滚

----------------------------------------------------
超纲部分
git rebase 一个比较有优势的方案， 来解决多分支合并带来的冲突
git cherry-pick  选取代码片段