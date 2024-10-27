# help

# 前言
	既然大家选择加入了我们，
	我们相信大家都是有一定的学习能力的，
	大家都是潮实学子 能来到这里说明学习能力都不差，
	我们建议遇到问题自己先尝试解决，查阅相关文档，确实解决不了的再请教，
	就像平时在校学习文化知识一样。
	
# 适用于
	本文假设您的开发平台是：
	1.搭载 Windows10 22H2 64位 操作系统的台式计算机或笔记本电脑，
	2.配备有足够的内存(memory)和存储空间(storage)
	3.搭载一颗性能基本足够的 64位 x86架构 CPU
	4.一双勤劳的双手
	5.一颗踏实的大脑
	
[正文]
	
# 准备事项
	0.如果你没有邮箱，先去注册一个来，下面用得到
	1.如果没有微软账户，请在此处注册 https://account.microsoft.com/account
	2.如果没有GitHub账户，请在此处注册 https://github.com/
	
# 工作应用
  任何方面的开发都离不开专业的开发工具，以下是我们推荐的应用：	
	
**1.VSCode** 
	一款由微软出品的强大的代码编辑器，搭配相应的拓展 和 开发环境，可以完成许多程序设计语言的 编写-编译-调试-部署 流程。
	下载链接(点击页面上的Download For Windows按钮)： https://code.visualstudio.com/ 
	
**2.Notepad3**
	一款文本编辑器，可以代替老旧的 Windows记事本.
	
**3.Intellij IDEA**
	一款适用于Java开发的IDE.下载时请选择社区版本(IDEA Community)
	下载链接 https://www.jetbrains.com/zh-cn/idea/download/?section=windows
	请在页面下滑选择 Intellij IDEA Community 下载 !!!
	
**4.DEV CPP**
	一款集成了C/C++运行环境的IDE，如果你只是想编写极其简单的C/C++程序，你可以选择这个.
	安装教程 https://zhuanlan.zhihu.com/p/599443944
	
**5.PyCharm**
	一款专门为Python打造的IDE，如果你是从事Python项目学习，可以选择这个.
	
**6.Adobe系列应用**
	Adobe公司的办公应用是生产力话题永远绕不开的。我们所熟知的Ps、Pr、Ae等都属于这个“Adobe全家桶”
	由于某些不可抗力因素，如果你需要下载adobe系应用，我们建议优先咨询社团群管理员
	
**7.Blender或Cinema4D (即C4D)**
	Blender和Cinema4D这两个应用都是建模和动画应用中的巨头，视个人喜好选择，我们推荐Blender。
	
**8.ToDesk**
	远程控制工具，用于远程协助.
	(需要高级功能的话可以考虑使用 Parsec)
	
# 改造你的设备
	1.更换搜索引擎为微软必应(bing)
	
	2.我们强烈建议你将浏览器换为 Microsoft Edge ，但并不强求。
		对于Edge浏览器，请做到：
		- 注册并登录你的微软账户。一个微软账户可以帮到你许多(真的很多)
		- 将Edge主页设置为新标签页，并在新标签页右上角的设置处，关闭一切不必要的超链接和广告推送
		- 打开垂直标签栏(视个人喜好而决定是否这么做)
	
	3.使用 Windows Terminal 替代原生的 cmd (如果你是 win11 系统，则可以无视本条)
		- 在系统里找到"微软商店"应用，搜索Terminal，并等待安装完成
		- 按Win+R键打开"运行'窗口
		- 输入 wt 并回车，今后你都可以通过输入 wt 来启动 Windows Terminal
		- 在弹出的Windwos Terminal窗口中，单击上方标签栏的齿轮按钮
		- 进入配置页面，设置 CMD 和 Powershell 都以管理员身份运行
		- 重启 Windows Terminal 即可
	
	4.配置Windows自带的包管理器winget，并换源 (如果未安装Terminal,请参照数字第三条)
		winget配置方法：
		- 进入配置页面，设置 CMD 和 Powershell 都以管理员身份运行
		- 重启 Windows Terminal 即可
		- 按Win+R键打开"运行'窗口
		- 输入 powershell 并按回车键
		- 在弹出的Powershell窗口中按以下方式操作：
			输入 winget source remove winget
			按回车(ENTER)键，等待完成
			输入 winget source add winget https://mirrors.ustc.edu.cn/winget-source --trust-level trusted
			按回车(ENTER)键，等待完成
		- 重启 Windwos Terminal
	
	5.安装 Git (Git是一个非常非常非常重要的东西)
		- 打开Terminal
		- 输入 winget install Git.Git 并回车，等待安装完成.
	
	6.安装 NeoFetch (本项可选。不必要，但有那么一点点一点点作用)
		- 打开Terminal
		- 输入 winget install neofetch 并回车，等待安装完成
