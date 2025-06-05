> fork by https://github.com/lmm214/memos-bber，兼容 Firefox/Chrome
Firefox 应用商店：<>

打包方法：

```
zip -r memos-bber-firefox.zip manifest.json _locales assets css js popup.html LICENSE README.md
```

---
## 说明

Chrome 应用商店：<https://chrome.google.com/webstore/detail/memos-bber/cbhjebjfccgchgbmfbobjmebjjckgofe/>

一个通过浏览器插件发布 [Memos](https://usememos.com/) 的插件。基于 iSpeak-bber 修改，原作者为 [DreamyTZK](https://www.antmoe.com/)。

## 更新日志

2024.07.21 不兼容更新，已匹配 v0.22.3

2024.06.15 感谢好心人 [PR#44](https://github.com/lmm214/memos-bber/pull/44)

2024.05.20 更新匹配至 v0.22

2023.09.19 不兼容更新匹配 Memos v0.15 的 `Access tokens` 模式。

<img width="483" alt="123" src="https://github.com/lmm214/memos-bber/assets/1472390/4ce2edc2-ce64-44d5-b4ef-d2e79b9d6a1a">

2023.07.16 支持 Memos v0.14.0 `api/v1`，同时兼容之前的 api。 

2023.04.29 右键菜单的一系列改进，感谢 @EZForever 的 PR [#17](https://github.com/lmm214/memos-bber/pull/17)

2023.04.09 匹配 v0.12.0 附件链接由 filename 改为 publicId 。

2023.03.25 右键菜单发送文本改为“追加模式”（不刷新已打开页面、不刷新已打开页面、不刷新已打开页面时）；新增多语言支持（en、zh-cn）。

2023.03.19 上传图片重命名精确的秒；打开插件时 focus 输入框（配合右键发送文本到扩展，设置快捷键打开扩展，按下 Ctrl+Enter 记下）。

2023.03.10 修复发布后调用最新一条 Memos。

2023.03.09 新增右键发送文本至 Memos 输入框。

![iShot_2023-03-05](https://user-images.githubusercontent.com/1472390/222957393-fc2e933e-b18f-4e69-a8c0-4609f84a0a90.png)

2023.03.05 新增指定标签“仅自己可见”或“所有人可见”；图片上传文件名添加时间戳。

2023.02.26 更改 Memos 可见范围按钮样式。支持 Ctrl/Meta + Enter 记下。点击标题跳转主站。

2023.02.25 修复 v0.11.0 下随机按钮失效。（api amount 失效导致，换用 stats 获取总条数）

![iShot_2023-02-06_19 16 28](https://user-images.githubusercontent.com/1472390/216958098-1f4fab2a-e77c-41bd-8ba3-5786f42744d7.png)

2023.02.07 新增发布后显示最新一条 Memo ，具体一条新增归档按钮。

2023.02.06 新增搜索按钮；新增图片灯箱。

![iShot_2023-02-04_20 42 40](https://user-images.githubusercontent.com/1472390/216768533-4a93124a-666e-4617-a60b-29c826dc1584.png)

2023.02.05 随机 Memos 支持指定标签 （算是彩蛋：标签列表点开，输入框内有且只有1个标签时，点击随机按钮）

2023.02.04 新增随机 Memos 按钮，随时唤醒记忆。

2022.11.15 新增插入文件图片按钮，尝试修复首次安装需要点一下小锁。

2022.11.13 新增插入 todo 按钮。

2022.11.8 支持拖拽上传附件（一个个传）。

2022.10.24 添加 visiblity 发送设置。

