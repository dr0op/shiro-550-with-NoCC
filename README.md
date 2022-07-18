# Shiro-550-with-NoCC

Shiro550 无Commons-collections依赖利用工具：

1. 使用Shiro自身利用链，不依赖Commons-collections库

2. 命令回显，依赖tomcat，支持tomcat7

3. 无限制命令执行，去除java命令执行不能使用管道和重定向符号的限制，如：

   ```shell
   cat /etc/passwd | grep root; echo 8416e1521a05a271074df8417177d090 > /tmp/1; cat 1
   ```

   ```shell
   root:x:0:0:root:/root:/bin/bash
   8416e1521a05a271074df8417177d090
   
    命令执行成功
   ```
# 免责声明
该工具仅用于安全研究、企业安全自查使用，请勿用于非法用途。

# REFERENCE
https://www.leavesongs.com/PENETRATION/commons-beanutils-without-commons-collections.html



   
