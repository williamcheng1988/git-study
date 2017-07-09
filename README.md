# git-study

#### 前提：安装git到本地
#### 1. 生成公钥  命令  `ssh-keygen`
出现的提示，连续回车(连续回车，表示使用默认配置)：

`Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/lenovo/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/lenovo/.ssh/id_rsa.
Your public key has been saved in /c/Users/lenovo/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:sFARj7oUVrOA/Awm5wHj/VE7Cp+KV5BM192zcL0AbHI lenovo@lenovo-PC
The key's randomart image is:
+---[RSA 2048]----+
|oo o..B+o.o .    |
|o.@ o+.B.E = .   |
| * @+.+o= o + .  |
|  ..B++o.  . .   |
|    o*. S        |
|  ..o.           |
| . o.            |
|  .              |
|                 |
+----[SHA256]-----+`

#### 2. 配置使用git仓库的人员姓名  
`git config --global user.name "wiliam"`
  
#### 3. 配置使用git仓库的人员email  
`git config --global user.email "williamcheng1988@gmail.com"`
