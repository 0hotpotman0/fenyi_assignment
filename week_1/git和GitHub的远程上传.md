##git和github的远程程序上传

>1. create a new repository on the command line
>**一下是一些在git上将本地上传到github的的操作指令**
>**记得在github创建一个新的repository**
>
echo "# learn_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/0hotpotman0/learn_git.git
git push -u origin master

>>  1. push an existing repository from the command line 
>**将已经存在的仓库push到到这个远程仓库**
git remote add origin https://github.com/0hotpotman0/learn_git.git
**这里的 "ogrigin" 是这个远程仓库的代号，可以自行修改**
git push -u origin master





****

##SSH的公钥和私钥的创建（很重要）

>ssh-keygen -t rsa -C "打入自己创建的email就行"
![avatar](C:\Users\Administrator\Desktop\git_basic_operation\创建公私钥图片.png)

>cd /c/Users/Administrator/.ssh
>**这个是根据自己创建SSH所在的路径，里面有一个私钥和公钥，私钥前往别泄露，公钥可以**

>>**这时需要复制公钥➡到GitHub的setting➡SSH and GPG keys➡在New SSH key创建一个后将公钥放进**
>
>ssh -T git@github.com
>**在git里面操作这个，这个是认证github和git的关系** 
