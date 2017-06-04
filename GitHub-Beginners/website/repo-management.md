## [萨满喵喵 ヽ(￣ω￣(￣ω￣〃)](https://emlvirus.github.io/)

## 管理个人项目 Repo Management

充分利用 GitHub 管理功能对于效率十分重要，此处为具体介绍

Utilize GitHub features to optimize efficiency. Here are details

以下内容在 `issue` 与 `pull request` 均类似，故以 `issue` 为例；有区别者会另作阐述

---

## 议题与 pull request 管理 Mange Issues & pull request

利用议题与 `pull request` 管理功能能使你的当前目标更加明确 Issue & pull request management can be expected to clarify your current goal

![](..\images/issue manage.png) 1 议题筛选 `Filters` ，可按照多种方式筛选现有议题，类似于 Excel 数据筛选。已添加的筛选条件及格式会实时显示在搜索框。

2 议题标签 `Labels` 管理。可以按照你的需要添加、修改标签文字颜色或者删除。删除标签的同时会删除 **已贴上该标签的所有 issue 与 pull request**

3 里程碑 `Milestones` 。为 `issue` 与 `pull request` 添加里程碑可以表示将会于何时解决

4 创建新议题 `issue` ；在 `pull request` 页面中同一位置的按钮即为创建新 `pull request`

5 复选框（仅你的项目可见）。最上方的一个为全选或全不选，标题旁为单项复选。选择之后可以对其进行操作（见下一部分）；点击 `Closed` 查看已关闭的 `issue` 与 `pull request` ，点击 `Open` 返回（默认仅显示仍打开 `Open` 的 `issue` 与 `pull request`）。

6~10 各种快速筛选条件，可与 1 结合使用，分别为创建人 Author 、标签 Labels 、里程碑 Milestones 、负责人 Assignee 、时间热度排序或出现最多的 emoji 表情符号

此外在 `pull request` 页面中 ![](..\images/review.png) 表示按照代码复查情况的筛选

---

## 对issue与pull request的标记操作 Mark Your Issues & pull request

**在你的项目中**，使用复选框选中至少一个 `issue` 与 `pull request` 之后，UI 变更如下

**In your repo** , select at least one `issue` 与 `pull request` , UI changes to:

![](..\images/mark issue.png) 1 若当前显示 Open的 `issue` ，点击 `Mark as` ，选择 `Closed` 即可关闭；反之，点击 `Mark as` 中的 `open` 将关闭的 `issue` 重新开启；若在 `pull request` 页面中则为撤销已经合并的代码

2/3 添加标签`Label`及里程碑 `Milestone`，如不合适在搜索框旁对应按钮处编辑即可

4 指定 `Assign` 负责人；若当前项目存在合作人 `collaborator` 而你为所有人 `Owner`，则可指定其中任意一人，否则**仅可**指定自己；若为组织账户 `Organization` 则可以指定组织中任意用户

以上 2~4 操作等效于 `issue` 与 `pull request` 详情页（点击任何项目的 `issue` 与 `pull request` 标题即可进入）右侧的操作按钮，如下图

![](..\images/issue details.png)

1 操作等效于详情页的 ![](..\images/close issue.png) 按钮；在 `pull request` 页面中等效于相同位置的关闭按钮

此外`pull request`页面中`Merge`按钮为接受合并；在接受合并前，请注意系统自动检查情况，出现红叉则建议手动合并

* 此外无论在任何人的项目中，若 `issue` 或 `pull request` 已经使用标签 `Label` 、里程碑 `Milestone` 、负责人 `Asignee` 等标记，点击该标记即可快速查看改分类
* **在你的项目中**，你可以点击![](..\images/lock conversation.png)来将当前 `issue` 或 `pull request` 的讨论限制在所有人 `Owner` 与合作人 `collaborator` 之间；之后，你可以点击同一位置的 ![](..\images/unlock conversation.png) 来解除限制
* Plus, no matter which repo it is, if this issue or pull request is marked with a Label, Milestone, Asignee, etc, click it to access such category
* **In your repo**, you can click ![](..\images/lock conversation.png) to allow conversation only between Owner and Collaborator. You can later click ![](..\images/unlock conversation.png) to remove the restriction

---

## 标签 Labels

**在你的项目中**，你可以编辑你的标签 `Labels` 以更好地管理 `issue` 与 `pullrequest`

**In your repo**, editing your `Labels` can help manage better

点击搜索框旁的按钮即可进去编辑页面，其中标签 Labels 编辑页面如下： Here is UI for Labels editing page:

![](..\images/label edit.png)

1 转到里程碑 `Milestones` 页面，见下一部分

2 创建新标签，点击后输入，选择颜色，点击 `Create label` 即可

3 排序：按照字母与使用次数等

4 编辑，修改颜色与名称

5 删除。删除标签的同时会删除 **已贴上该标签的所有 issue 与 pull request**

---

## 里程碑 Milestones

里程碑 `Milestones` 也是另一个有效的管理方式，用于安排表明项目进程。管理 UI 如下：

![](..\images/milestone UI.png)

1 类似于 `issue` 中切换显示 `Open` 与 `Closed`

2 显示创建时提供的标题、描述、到期时间，并显示最后修改时间

3 完成进程，即标记有这个里程碑 `Milestone` 的 `issue` 中有多少已经被 `closed` ；

点击 Edit 即可编辑里程碑 `Milestone` 信息；`close` 关闭，则不再显示；点击 `Delete` 永久删除

4 排序，可按照修改时间、到期时间、标记的 `issue` 数量、完成度等进行排序

5 新建里程碑 `Milestones`，点击后输入标题、描述（可不填）并选择到期时间（可不选），点击 `Create milestone` 即可创建；过程中点击右上角的 `clear` 清空已填内容

###### [啊啦 乃手滑了](..\index.html#table-of-contents)
