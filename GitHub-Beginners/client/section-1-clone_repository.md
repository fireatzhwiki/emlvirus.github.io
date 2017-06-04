## [萨满喵喵 ヽ(￣ω￣(￣ω￣〃)](https://emlvirus.github.io/)

## 使用 Visual Studio 内置的 Github 客户端克隆代码

![](..\images/the-clone-button.png)

在每一个 Github 网站上面的 repository 的首页之中，我们都能够看见一个绿色的代码克隆菜单。在克隆菜单之中可以看见，有三个按钮：

1. **Open in Desktop**: 使用 Github Desktop 客户端打开
2. **Open in Visual Studio**: 使用 Visual Studio 之中内置的官方 Github 客户端打开
3. **Download ZIP**: 仅下载当前分支的源代码包

在这里我们将会详细介绍如何使用 Visual Studio 进行 Github 上面的 repository 的克隆操作。

当我们点击了 `Open in Visual Studio` 这个按钮之后，浏览器将会弹出一个 URL Protocol 的对话框，提示我们是否允许 Github 网站启动 Visual Studio 程序。在这里为了能够使用 Visual Studio 进行 repository 的克隆操作，这里选择从浏览器弹出来的对话框之中的左边的按钮， `Open Microsoft Visual Studio Github Handler Selector` 进行授权。

![](..\images/open-visualstudio.png)

之后我们就能够看见 Visual Studio 已经通过 URL protocol 启动了，并且团队浏览器之中出现了我们将要进行克隆的 repository 的URL以及预置的本地目录路径。待克隆的 repository 在 Visual Studio 之中内置的 Github 官方客户端的默认保存路径为用户文件夹之中的 source 目录。如果想要保存在其他的路径，可以在直接在本地路径的文本框之中输入目录的路径，也可以点击最右边的带有 `...` 的按钮打开文件夹浏览器选择，例如：

![](..\images/vs-team-explorer.png)

在弹出来的对话框之中选择好想要保存的文件夹的路径，然后点击 `OK` 确认即可。
![](..\images/select-local-directory.png)

最后，我们点击 `Clone` 按钮即可开始代码的克隆操作。

![](..\images/clone-progress.png)

在 Visual Studio 对我们的目标 repository 的 clone 操作之中，我们可以很清楚的了解到当前的克隆进度以及数据的下载速度。例如在上图之中，我们可以了解到，当前的克隆进度为 `3295/52375 * 100% = 6.29%` ，代码的下载速度为 `22.00KiB/s` 。或许我们只需要喝一杯咖啡，休息一下大脑，慢慢等待克隆操作的进度条走完即可。

###### [啊啦 乃手滑了](..\index.html#table-of-contents)
