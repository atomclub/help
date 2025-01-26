# 帮助文档 - 环境搭建必读
> 你可以在知乎 [zhuanlan.zhihu.com/p/20378256562] 找到这篇教程的转载

# 前言
既然大家选择加入了我们，我们相信大家都是有一定的学习能力的，大家都是潮实学子 能来到这里说明学习能力都不差，我们建议遇到问题自己先尝试解决，查阅相关文档，确实解决不了的再请教，就像平时在校学习文化知识一样。
	
# 适用于
本文假设您的开发平台是：
1. 搭载 Windows10 22H2 64 位 操作系统的台式计算机或笔记本电脑，
2. 配备有足够的内存 (memory) 和存储空间 (storage)
3. 搭载一颗性能基本足够的 64 位 x86 架构 CPU
4. 一双勤劳的双手
5. 一颗踏实的大脑
	
# 准备事项
1. 如果你没有邮箱，先去注册一个来，下面用得到
2. 如果没有微软账户，请在 [此处](https://account.microsoft.com/account)注册
3. 如果没有 GitHub 账户，请在[此处](https://github.com/) 注册
	
# 工作应用
任何方面的开发都离不开专业的开发工具，以下是我们推荐的应用：	
	
## 1. VSCode
一款由微软出品的强大的代码编辑器，搭配相应的拓展 和 开发环境，可以完成许多程序设计语言的 编写 - 编译 - 调试 - 部署 流程。	

下载链接 (点击页面上的 Download For Windows 按钮)：https://code.visualstudio.com/ 

 
## 2. Notepad3
一款文本编辑器，可以代替老旧的 Windows 记事本。

## 3. Watt Tool Kit (旧名:Steam++)
一款网络加速工具，初衷是为某国外游戏平台加速，但后来人们发现它的功能远不止这些。
可以用于加速GitHub、CloudFlareCDN、GoogleRecaptcha等网站/验证码收发。
可以小程度代替代理来使用。~~但站点要是被墙了就无能为力了~~
 
## 4. Intellij IDEA
一款适用于 Java 开发的 IDE. 下载时请选择社区版本 (IDEA Community)

 [下载 IntelliJ IDEA – 领先的 Java 和 Kotlin IDE](https://www.jetbrains.com/zh-cn/idea/download/?section=windows)
 
**请在页面下滑选择 Intellij IDEA <mark>Community</mark> 下载 !!!**

 
## 5. DEV CPP
一款集成了 C/C++ 运行环境的 IDE，如果你只是想编写极其简单的 C/C++ 程序，你可以选择这个。
安装教程 [https://zhuanlan.zhihu.com/p/599443944](https://zhuanlan.zhihu.com/p/599443944)

## 6. PyCharm
一款专门为 Python 打造的 IDE，如果你是从事 Python 项目学习，可以选择这个。

 
## 7. Adobe 系列应用
Adobe 公司的办公应用是生产力话题永远绕不开的。我们所熟知的 Ps、Pr、Ae 等都属于这个“Adobe 全家桶”。由于某些不可抗力因素，如果你需要下载 adobe 系应用，我们建议优先咨询社团群管理员。

 
## 8. Blender 或 Cinema4D (即 C4D)
Blender 和 Cinema4D 这两个应用都是建模和动画应用中的巨头，视个人喜好选择，我们推荐 Blender。

 
## 9. 向日葵 / Todesk
远程控制工具，用于远程协助，但推荐使用前者。
(需要高级功能的话可以考虑使用 Parsec 或 自建 RustDesk )

 
# 改造你的设备
### 1.更换搜索引擎为微软必应 (Microsoft Bing)
	
### 2.我们强烈建议你将浏览器换为 Microsoft Edge，但并不强求。
对于 Edge 浏览器，请做到：
- 注册并登录你的微软账户。一个微软账户可以帮到你许多 (真的很多)
- 将 Edge 主页设置为新标签页，并在新标签页右上角的设置处，关闭一切不必要的超链接和广告推送
- 打开垂直标签栏 (视个人喜好而决定是否这么做)
	
### 3.使用 Windows Terminal（终端） 替代原生的 cmd (如果你是 win11 系统，则可以无视本条)
- 在系统里找到"微软商店"应用，搜索 Terminal 或 终端，并等待安装完成
- 按 Win+R 键打开"运行'窗口
- 输入 `wt` 并回车，今后你都可以通过输入 `wt` 或“终端”来启动 Windows Terminal
- 在弹出的 Windwos Terminal 窗口中，单击上方标签栏的齿轮按钮
- 进入配置页面，设置 CMD 和 Powershell 都以管理员身份运行
- 重启 Windows Terminal 即可
	
#### 4.配置 Windows 自带的包管理器 winget，并换源 (如果未安装 Terminal，请参照数字第三条)
winget 配置方法：
- 进入配置页面，设置 CMD 和 Powershell 都以管理员身份运行
- 重启 Windows Terminal 即可
- 按 Win+R 键打开"运行'窗口
- 输入 powershell 并按回车键
- 在弹出的 Powershell 窗口中按以下方式操作：
    - 输入 `winget source remove winget`
    按回车(ENTER)键，等待完成

    - 输入 `winget source add winget https://mirrors.ustc.edu.cn/winget-source --trust-level trusted`

    - 按回车 (ENTER) 键，等待完成
- 重启 Windwos Terminal
	
### 5.安装 Git (Git 是一个非常重要的版本管理系统，即 VCS)
- 打开 Terminal
- 输入 `winget install Git.Git` 并回车，等待安装完成。
	
### 6.安装 NeoFetch (可选)
- 打开 Terminal
- 输入 `winget install neofetch` 并回车，等待安装完成
