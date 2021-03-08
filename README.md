##### git 是什么？ 用途是？
- git 是一个**分布式版本控制软件**, 由**林纳斯·托瓦兹**创作,
- 最初目的是为更好地**管理 Linux 内核开发**而设计
- git的作用就是**对文件进行版本管理**, 方便在**不同版本**进行**切换修改**, 类似文件分**不同时间备份**然后需要时, 找回其中一份**代替**, 不过更**方便使用**

----

##### git 常用命令
- **git branch** 查看分支
- **git checkout feature/xiejianxiong** 切换到自己的分支
  - PS: 如果想新建一个分支，执行以下命令
    - **git checkout -b feature/xiejianxiong**
- **git pull origin develop** 从 develop 拉代码到当前分支并合并
  - PS: 如果提示有冲突，执行以下命令
    - **git stash** 缓存
    - **git pull origin develop** 从develop 拉代码 手动解决代码冲突
    - **git stash pop** 从缓存中拿取数据，并且手动合并冲突
- **git status** 查看当前状态
- **git add .** 将所有文件改动都添加到暂存区 (add 后面有个点)
- **git commit -m "备注"**  提交代码
- **git push origin feature/xiejianxiong** 推送代码到服务器


----

##### git reset 和 git revert
- 回滚代码 切换到指定 commit id


- 总结 2 句话
  - git revert 后会**多出一条 commit**，这里可进行**回撤**操作
  - git reset 直接**把之前 commit 删掉**，非 git reset --hard 的操作是不会删掉修改代码，如果远程已经有之前代码，需要强推 git push -f

##### git submodule 



##### git proxy


##### git hook


##### git flow


##### git GUI 工具
小乌龟
source tree
1
2
