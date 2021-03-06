## [萨满喵喵 ヽ(￣ω￣(￣ω￣〃)](https://emlvirus.github.io/)

## Q1：影响音质的因素

* 音频文件的制作规格，如`采样率`，`位深`等
* 声卡
* 最终输出硬件（很有可能是音箱）的制作工艺及相关输出技术
* **没有播放软件**，**没有播放软件**，**没有播放软件**

---

## Q2：播放器能影响什么？

答案很简单：`音效`

---

当你使用了某些仅允许一个进程调用的 API，如 `WASAPI`，防止别的软件杂音干扰，或是使用均衡算法，微调频谱图形令总体声音圆润，这都改善听感。然而影响的仅仅是`音效`而不是`音质`，并且所有的主流播放器都能做到。换个播放器就能提高音质完全是 tan 90° 。

---

## Q3：无损/有损的准确定义

对于无损/有损，描述的都是音频压缩算法：当压缩后文件中的信息能完整还原成压缩前，即算法可逆，该压缩算法即称无损，例如 `WAV` → `FLAC`；反之，信息无法完整还原，算法不可逆，即为有损，例如 `WAV` → `MP3`。

**当不涉及压缩算法的范畴，也就不涉及有损无损的概念**，因此 `WAV 无损` 这一概念本身自相矛盾。

---

## Q4：为什么不能说 `WAV` 代表音质无损失

```
请记住一点：格式是容器，内容显然比格式更重要
```

如果你将一个码率为 192kbps 的 MP3 文件转格式为 WAV，然后跟码率为 320kbps 的 MP3 比较会得出什么结论？结论基本如下：

* 有损格式确实会导致音质的损失（小杯子装得水当然少），但是无损格式不一定内容是无损的（大杯子装的水未必比小杯子多）

### LICENSE
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a> Except where otherwise noted, all contents in this site is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0 International License</a>.

###### [啊啦 乃手滑了](..\homepage.html#table-of-contents)
