~# oss help
# 登陆恒源云账号，使用恒源云的账号名与密码，账号名为手机号
# 如果是非中国大陆手机号码，需要加上带 + 的区号
~# oss login
Username:139********
Password:***********
139******** login successfully!

#查看个人数据中的datasets目录
 # oss ls -s -d oss://datasets/
Listing objects .
Folder list:
oss://datasets/
Object list:
oss://datasets/个人数据.zip
Folder number is: 1
File number is: 1

#下载个人数据到/hy-tmp/目录下
~# oss cp oss://datasets/个人数据.zip /hy-tmp/

#查看已下载到/hy-tmp/目录中的数据
~# ls /hy-tmp/
