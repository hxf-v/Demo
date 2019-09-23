使用git将本地文件上传到github
步骤：
    1、创建或修改本地文件
    2、使用git add 命令，将创建或修改的文件添加到本地的缓存区
    3、使用git commit 命令，提交文件到本地仓库
    4、使用git push 命令，将本地代码库同步到github
    

具体示例：
        1、新建文件夹（存放要上传的文件）
        2、输入git init 命令，初始化git仓库（作用：将一个已存在文件夹，置于 Git 的控制管理之下）
        3、git add test.py (添加想要上传的代码）
        4、git config --global user.name "YourName"
        5、git config --global user.email "YourEmail@xxx.com"（本地配置github用户名、用户邮箱）
        6、git remote add origin 仓库链接（将本地仓库连接到 GitHub 仓库中）
        7、git push origin master（ 使用 push 可以把本地仓库推送到远端仓库中）
        8、刷新一下网页就可以看到文件已经上传到github上了。
      
