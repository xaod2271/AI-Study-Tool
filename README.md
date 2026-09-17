# MySQL复习工具（现已支持多学科）

**通用学科学习与 AI 复习工具 / AI Study & Review Tool**

上传自己的笔记、课件或文档，自动识别学科、提炼知识点、生成练习，并根据回答给出点评。支持编程、数学、英语等学习场景，也可用于其他学科资料的复习。项目从 MySQL 复习工具扩展而来，仓库名称暂时保留。

## 下载通用学科版

**[打开下载页面](https://github.com/xaod2271/MySQL-Review-Tool/releases/tag/v0.4.3)**

| 系统 | 下载 | 要求 |
| --- | --- | --- |
| Windows | [Windows 0.4.3](https://github.com/xaod2271/MySQL-Review-Tool/releases/download/v0.4.3/XiaodingReview-Windows-x64-0.4.3.zip) | Windows 10/11，Intel / AMD 64 位 |
| Mac | [Mac 0.4.2](https://github.com/xaod2271/MySQL-Review-Tool/releases/download/v0.4.3/XiaodingReview-macOS-universal-0.4.2.zip) | macOS 13+，Apple 芯片 / Intel |

这是加入满分庆祝动画之前的版本，不包含该特效。两端包保留各自已完成版本号，Windows 0.4.3 包含旧后台接管修复。无需安装 Python、Node.js 或 MySQL。请下载应用 ZIP，GitHub 自动生成的 Source code 压缩包不是安装包。校验文件见 Release 附件。

## 开始使用

1. 解压下载包；Windows 双击「启动复习室.cmd」，Mac 打开「小玎的复习室.app」。
2. 在「连接设置」填写自己的 DeepSeek API Key，保存并测试连接。
3. 上传学习资料，学科留空即可自动识别；等待 AI 整理核心知识。
4. 按学科、知识模块、题型选择练习，一问一答并查看点评。

## 功能

- 自动识别学科，混合文档可分科整理；知识点保留原始出处。
- 按知识内容匹配选择、简答、代码、计算、翻译、证明等题型。
- 默认围绕上传资料出题，也可选择允许拓展。
- 支持 PDF、Word、PPT、HTML、XMind、Markdown、文本和图片资料；单文件最多 50 MB。
- 后台处理队列、失败重试、学习进度、薄弱点复习、数据库备份。
- 同一 Wi-Fi 下可通过电脑共享给手机使用。

适配不同学科不等于所有学科均已验证。AI 识别、归纳与评分可能出错；复杂公式、图表及扫描内容请对照原文核查。每种题型是否可选取决于资料和整理结果。

## 数据、费用与更新

发行包为空资料库，不含作者的个人资料、成绩、密钥或访问码。AI 功能需要网络和自己的 DeepSeek 额度，相应资料及作答会发送至 DeepSeek。

学习数据存储于本机：Windows 为 `%LOCALAPPDATA%\XiaodingReview`，Mac 为 `~/Library/Application Support/XiaodingReview`。更换程序无需清空学习数据；升级前建议导出数据库备份。备份不包含 AI 密钥。

关闭网页不会退出后台。请在「连接设置」退出复习室后更换程序。手机共享仅用于可信任的同一 Wi-Fi。

## 验证与许可

Windows 0.4.3 通过 128 项后端测试、构建和包清单校验，Windows 真机尚未验证。Mac 0.4.2 通过 Apple 芯片原生、Intel 经 Rosetta 及启动/移动/备份恢复检查；Intel 真机和 Apple Developer ID 签名、公证未完成。

第三方运行环境和依赖的许可证随应用包提供。当前仓库提供应用下载与说明，未声明独立的项目开源许可。

检索关键词：AI 学习工具、AI 复习、智能出题、自动生成练习、多学科学习、学习助手、study tool、AI tutor、quiz generator、DeepSeek。
