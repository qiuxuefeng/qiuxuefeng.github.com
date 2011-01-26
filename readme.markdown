个人博客第一篇

git版本管理

比较关键的几个上传步骤：

			git init
                        git remote add origin git@github.com:qiuxuefeng/anren.git # 建立本地版本库与远程服务器的链接关系。
			git add .                                                    # 增加本地所有的文件
			git commit -a -m"第一次提交代码" （好像必须写）                           # commit命令主要表示将本地的修改提交到本地的版本库之中，a参数表示all的意思，m参数表示message的意思，主要是用于记录自己的写作或者编程过程。
			git push origin master                                       # push 命令主要表示推送本地的版本库到远程服务器上去。

参考文章：

[windows下使用git管理github项目](http://hi.baidu.com/mcspring/blog/item/171b1e38986d39fab211c71b.html)

[Git 使用指南](http://www.linuxgem.org/user_files/linuxgem/Image/git-tutor.pdf)


