git操作

git config --system --list

git config --global --list #用户信息

git本地提交远程

本地->git add提交到暂存区->git commint提交到本地仓库->git push提交到远程仓库

ssh密钥

1.GitHub创建仓库

2.将远程仓库克隆到本地（HTTP）->git clone "http"

​	2.1需要ssh密钥

​	2.2图形化界面生成公钥(help里面，密码不用输入)

![image-20251130160037489](C:\Users\wuzhe\AppData\Roaming\Typora\typora-user-images\image-20251130160037489.png)

![image-20251130160200057](C:\Users\wuzhe\AppData\Roaming\Typora\typora-user-images\image-20251130160200057.png)

​	2.3然后将公钥拷贝到GitHub里

![image-20251130160333767](C:\Users\wuzhe\AppData\Roaming\Typora\typora-user-images\image-20251130160333767.png)

3.在本地仓库目录里操作

git add 文件名/文件夹

git commit -m "解释说明"

git status

git push

