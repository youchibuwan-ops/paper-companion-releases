# 论文伴读 0.6.14 免费测试版

程序版本 0.6.14，发布标签 v0.6.14-beta.1，Windows x64。软件免费；AI 账户、API 额度和费用按所选服务商规则单独管理。

## 更新内容

- 移除整个网页对话功能，包括嵌入官网、自动发送与回答抓取。
- 保留旧网页问答及原论文、原选区和发送状态，支持离线只读查看；原来源由系统浏览器打开。
- 保留正常的 Codex、DeepSeek Harness 持续会话及 DeepSeek、Claude、Qwen API 接入，模型与档位不静默替换。
- 补齐第三方代码、数学字体、原生绘图、PDF与翻译组件的许可、版权和必要致谢。设置中的离线许可页可直接查看原文。
- 新模型下载固定上游修订并保存来源；已有缓存和人工译文保留，不补造旧来源。
- 检索结果增加来源、许可及摘录说明。新论文下载核验官方开放获取记录，PDF与来源成对保存；下载不可用时可直接打开正确原文。
- 修复旧打包格式升级后的程序残留，正常升级后可以再次安装更新；未知文件继续保留。

## 安装

下载附件 **PaperCompanion-Setup.exe** 并运行；默认D盘，也可选择其他空目录或已登记的程序目录。安装前关闭论文伴读窗口。应用数据独立于程序目录保存，原论文按原位置只读打开。安装包尚未数字签名。

独立附件 **PaperCompanion-Licenses-0.6.14.zip** 可解压离线查看全部许可材料；程序中也已包含这些文件。

## 发布检查

关键验证覆盖旧记录与准确锚点、网页新入口移除、原生会话与API参数、模型失败恢复、论文下载来源、实际包内许可、真实桌面启动和旧版升级再更新。AI协议测试使用隔离fixture，不以此宣称本轮已调用所有远端模型。

[第三方通知](https://github.com/youchibuwan-ops/paper-companion-releases/blob/main/THIRD-PARTY-NOTICES.txt) · [版本与来源](https://github.com/youchibuwan-ops/paper-companion-releases/blob/main/sources.json)

公开界面预览使用 Carey、Steiner、Petri Jr（2020）的 *Ten simple rules for reading a scientific paper*，[DOI:10.1371/journal.pcbi.1008032](https://doi.org/10.1371/journal.pcbi.1008032)，[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)，含软件高亮、中文讨论和界面裁切。所列AI服务名称用于说明接入方式，不表示官方合作或背书。

反馈请提供系统版本、软件版本和复现步骤，请勿上传密钥、私人论文或聊天记录。
