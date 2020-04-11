# learnGit
学习Git记录

## git 基础命令
	1、拷贝 ： git clone <厂库地址>
	2、创建分支：git branch <分支名>
	3、创建并进入分支：git checkout -b <分支名>
	4、查看状态：git status
	5、添加所有文件：git add
	6、提交：git commit -m '这里填写提交当前文件的描述'
	7、拉取：git pull
	8、推送：git push
	9、查看分支：git branch --list
	10、查看分支(包含远程分支)：git branch -a
	11、切分支： git checkout <分支名>
## github 检索
	1、location ： 地区
	2、language ： 语言
	3、stars:>500  星数大于500 
	4、forks:>500  分支大于500
	5、followers:>500 匹配超过500名开发者的开发者
	6、jackal in:fullname 匹配用户名叫 jackal 的用户
	7、Awesome + 关键字
	
## README.md 文件编辑
	1、#+" "+标题， 一个#为一级标题，以此类推
	2、单行显示 使用一个tab
### 测试


## github 加速
    1、首先打开 https://IPAdress.com 搜索github.com、assets-cdn.github.com、
        github.global.ssl.fastly.net的ip地址
    2、修改host文件
        添加：
        (```)
            windows 系统： C:\Windows\System32\drivers\etc
            140.82.113.3 github.com
            185.199.108.153 assets-cdn.github.com
            199.232.69.194 github.global.ssl.fastly.net
        (```)
    3、刷新cdn
        cmd 执行 ipconfig /flushdns

