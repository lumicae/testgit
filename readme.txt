Git安装完成后的初始化
1.打开 Git Bash
2.输入命令：git config --global user.name "lumicae"
	    git config --global user.email "lumicae@sina.com"
  Git 是分布式版本控制系统， 所以需要填写用户名和邮箱作为一个标识
  git config --global 参数表示 本机中所有的Git仓库都会使用这个配置
一、创建版本库
   cd D:
   cd gitRepostiory
   mkdir testgit
   cd testgit
   pwd  //输出/d/gitRepository/testgit,pwd命令用于显示当前的目录
 1.通过命令git init 把目录testgit变成git可以管理的仓库，这时testgit目录下会多了一个.git的目录，.git是Git来跟踪
   管理版本的，不要更改该文件夹
 2.把文件添加到版本库在testgit下创建文件readme.txt,输入一些内容并保存
   第一步： 使用命令 git add readme.txt添加到暂存区里面
   第二步： 使用命令 git commit -m "readme.txt提交" 把文件提交到仓库 -m 后的字符串是提交的注释
   第三步： 使用命令 git status 查看是否还文件未提交
   第四步： 修改readme.txt文件内容，继续使用git status查看结果
   第五步； 使用 git diff readme.txt查看readme.txt文件到底改了什么内容
   第六步： 使用命令 git add readme.txt,git commit -m "增加内容第四五六步"
二、版本回退
   继续对readme.txt文件进行修改 ，然后add 和 commit