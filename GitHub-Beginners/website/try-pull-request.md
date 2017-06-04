## [萨满喵喵 ヽ(￣ω￣(￣ω￣〃)](https://emlvirus.github.io/)

## 尝试创建Pull Request参与贡献 Try Your Own Pull Request

---

尝试对代码项目作出贡献的办法就是发起 `pull request` 。此处介绍如何发起一个 `pull request` ，指向他人的代码项目。

* 一个 `pull request` 的创建前提就是代码差异，比较双方可以是项目的不同分支 `branch` 、项目原本与他人的复刻本 `fork` 等

此处以 `fork` 之后翻译他人的 XML （可用于存放程序 UI 中的字符串）为例：

The way to contribute to a repo is a pull request. Here is how, against repo of others.

* the premise of a `pull request` is code difference, compared across `branches` ,  `forks` , etc.

Here is an example as translating XML (storing UI strings) in a `fork` :

![](..\images/fork.png) 首先在他人项目主页右上角点击 `fork` ，创建复刻以获取所有权限（如上图红框） you will have to fork first for access writing right (as red box above)

等待完成后（注意上下两图左上角项目名称上的差异），找到需要修改的文件，单击浏览源代码，点击 ![](..\images/edit file.png)开始编辑

wait until finished (please notice difference about repo name between two sreenshots), find any file, click to see source code and click ![](..\images/edit file.png) to start.

![](..\images/fork down.png)

此例中，选择 Zh-CN.xml ，点击即可查看源码（如下图红框） In this case, select Zh-CN.xml (as the red box below)

![](..\images/select file.png)进入源代码后点击 ![](/assets/edit file.png) 即可开始编辑源代码（如下图）

click ![](..\images/edit file.png)to start editing source code (as screenshot below)

修改完成后点击 ![](..\images/commit change.png) 来提交你的修改 click `commit changes` once you are done

回到原有项目中，点击 ![](..\images/new pull request.png 来创建一个 `pull request`；click `New pull request` to create one in former repo

点击 `compare across forks` 并找到属于你的 `fork` （可见于用户名），如下图所示

![](..\images/compare fork.png) 随后输入相关描述信息：标题、描述等（建议填写尽可能详细的信息方便他人，也可忽略），点击 `Create pull request` 即可完成

add more details to your `pull request` and click `Create pull request`

![](..\images/create pull.png)

随后项目原本所有人便会在项目主页的 ![](..\images/see pull.png) 处看到相关信息，以下为一个已接受的例子：

* 只有项目所有人 `Owner` 和合作人 `collaborator` 有权接受合并

By now `owner` of former repo will notice it. Here is a merged example:

* only `Owner` and`collaborator` will have right to merge

![](..\images/pull merged.png)

以下为一个被关闭（拒绝）的例子：

* `pull request` 发起人、项目所有人 `owner` 和合作人 `collaborator` 均有权关闭

Here is a closed example:

* creator of `pull request` , `Owner` and `collaborator` will all have right to close

![](..\images/pull closed.png)

###### [啊啦 乃手滑了](..\index.html#table-of-contents)
