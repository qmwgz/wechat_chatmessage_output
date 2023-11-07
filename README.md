# wechat_chatmessage_output
# 小米手机到处记录

1. 备份记录，先备份到手机，在拷贝到电脑
2. 准备7zip软件，必须是7zip,解压
3. 找到目录里面sp目录里面的auth_info_key_prefs.xml文件<int name="_auth_uin" value="-11111111" />
4. 找到数据库文件E[com.tencent.mm](http://com.tencent.mm/)\r\MicroMsg目录下目录名最长的，找到EnMicroMsg.db
5. 拼接密码1234567890ABCDEF-11111111
6. 把以上密码用md5进行加密，加密地址[MD5 Hash Generator,Sha1 Hash Generator--Md5 decrypt online (cmd5.org)](https://www.cmd5.org/hash.aspx?s=123456)
7. 得到密码后，用sqlcipher.exe打开输入密码
8. 导出数据到csv文件中
