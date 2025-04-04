# git ＆ github使用

## git

```
(注：以下命令均需要注意空格)
注册用户名命令行：$ git config --global user.name  用户名

注册邮箱命令行：$ git config --global user.emali  邮箱
（该邮箱可为不存在的虚拟邮箱）

初始化生成.git文件命令行：$  git init

项目克隆命令：$ git clone 网页

将工作区所有文件和非空文件夹（.git除外）全部存入暂存区：$ git add .

提交指定文件：$ git add 文件名

对本次提交进行注释：$ git commit -m “注释内容”
（注：注释一定要写，写完注释后代码就会被提交到仓库）

提交历史查询：$ git log

恢复文件：$ git check HEAD 文件名

```



## github

github中创建仓库后，在git中使用remote和push命令可将本地代码和github仓库连接

要添加一个新的远程仓库，可以指定一个简单的名字，以便将来引用,命令格式如下：

```
git remote add [shortname] [url]
```

如果使用ssh进行加密的话，需要配置验证信息，使用htts不需要这一步





## 在vscode里使用



