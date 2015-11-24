About Git.
name:DreamRui
email:dreamrui12589@gmail.com

步骤：

->sudo ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  下载超级大管家，进门。有时候需要去掉sudo才好用

#sudo:查看、修改或者执行某些命令需要root用户的权限，如果不想直接切换到root用户，就可以使用sudo命令。sudo命令用于针对单个命令授予临时权限。sudo仅在需要时授予用户权限，减少了用户因为错误执行命令损坏系统的可能性。

->git config --global user.name "DreamRui"
->git config --global user.email "1114095037@qq.com"
    github 用户名可以改，邮箱是登陆的邮箱！

->cat .gitconfig 查看当前的name email

->ssh-keygen -t rsa -C “1114095037.com”
  一路回车下去
  在根目录下，cat .ssh/id_rsa.pub
  把密钥拷贝至SSK KEY里

->新建仓库git clone https://github.com/DreamRui/afool.git
  里面随便写点文件

->git status

On branch master
Initial commit
Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file:   afool.txt

#里面会有错误，就要复制他提示的代码
比如：git branch --unset-upstream

->git add afool.txt
->git remote add origin https://github.com/DreamRui/afool.git
->git push
然后输入name password 就完事了

#回看很简单，但是路上遇到的问题却怎么都想不到
#明明很简单，却做的很复杂，成功就是简单的事用心做
#You need more concentration and patience
thanks for khahux ,I did not fall behind,to learn more
