# sublime_package_control
sublime package 被墙，改为国内地址


解决Sublime的package control被墙

Preferences > Package Settings > Package Control > Settings - User

User文件下添加
"channels":
[
"http://cst.stu.126.net/u/json/cms/channel_v3.json",
]


最终结果
{
	"bootstrapped": true,
	"channels":
	[
		"http://cst.stu.126.net/u/json/cms/channel_v3.json"
	],
	"in_process_packages":
	[
	],
	"installed_packages":
	[
		"Package Control",
		"Vue Syntax Highlight"
	]
}


重启
