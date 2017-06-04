## [萨满喵喵 ヽ(￣ω￣(￣ω￣〃)](https://emlvirus.github.io/)

## 使用 Visual Studio 进行 repository 的修改的 commit 及同步操作

不像 svn 管理系统，commit 是直接 commit 到中心服务器之上的，故而 svn 的 commit 操作必须要保证客户端和服务器是处于联网状态的。对于 git 源代码管理而言，则可以先将代码 commit 到本地的 repository 之中，然后在 push 到服务器上面的时候才会需要联网。

| | Local | Remote |
|---|--------------------------|---------------------------|
|svn| |[local] commit --> [remote]|
|git|[local] commit --> [local]|[local] sync <--> [remote]|

使用 Visual Studio 之中的 github 客户端进行源代码的保存操作大致需要经过两个主要步骤：

+ **local commit**, 本地提交
+ **sync with remote**, 与远程仓库同步，其实无论是 Github Desktop 客户端还是 Visual Studio 之中的 Github 官方客户端，都将 Fetch 和 Push这两步操作合并简化为了一步 sync 同步操作。

通过点击在 GitHub 客户端上面的 repository 的名称标签，将会打开一个菜单，例如：

![](..\images/basic-operations.png)

+ **Changes**: 修改更新的本地提交
+ **Branches**: 切换源代码的分支
+ **Sync**: 与远程服务器的同步操作， Github 客户端会先执行 `Fetch` 再执行 `Push`
+ **Projects**: 在不同的 repository 之间进行工作区切换
+ **Settings**:  Github 账号设置以及当前 repository 设置

###### [啊啦 乃手滑了](..\index.html#table-of-contents)
