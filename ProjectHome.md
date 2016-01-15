# 项目转移至 github #
http://zoeey.github.com/zoeeyguard/


易于定制的PHP源码加密扩展

# 特性 #
  * 通过简单配置即可实现自定义加密。
  * 加密过程清晰，易于定制。
  * 密文与扩展独立配套，安全性高。
  * 内置加密函数，方便写入部署脚本。

# 下载 #

源码：
http://zoeeyguard.googlecode.com/files/zoeeyguard-latest.zip

32位win平台扩展（dll）
http://code.google.com/p/zoeeyguard/downloads/detail?name=zoeeyguard-1.0-x86-win.zip

版本库：
```
svn checkout http://zoeeyguard.googlecode.com/svn/ zoeeyguard-read-only
```


# 手册下载 #

| 格式 | 地址 | checksum| 备注 |
|:---|:---|:--------|:---|
| chm  | [chm](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard.chm) | [checksum](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard.chm.checksum)| 无法查看：文件属性，解除锁定 |
| html  | [zip](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard.zip) | [checksum](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard.zip.checksum)|    |
| single  | [zip](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard-single.zip) | [checksum](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard-single.zip.checksum)|    |
| pdf  | [pdf](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard.pdf) | [checksum](http://zoeeyguard.googlecode.com/svn/trunk/doc/build/zoeeyguard.pdf.checksum)|    |


# 使用示例 #

源文件
index.php
```
<?php
    echo 'hello world';
?>
```

结果
index.php
```
<?php
  /* 2012-03-15 00:47:01 */
  zoeey_run('2Xr6JcrLv8w92M38Ul30w7IjUuQjhRO+S0rdw+ag');
?>
```

## 联系作者： ##
qq:59.43.59.0(接受定制服务)

email:system128 at gmail dot com


keywords: [PHP加密](http://code.google.com/p/zoeeyguard)，[PHP源码加密](http://code.google.com/p/zoeeyguard)，[PHP代码保护](http://code.google.com/p/zoeeyguard)


```
/*
 ________                                   
/\_____  \                                  
\/____//'/'    ___     __     __  __  __    
     //'/'    / __`\ /'__`\ /'__`\\ \/\ \   
    //'/'___ /\ \L\ \\  __//\  __/ \ \_\ \  
    /\_______\ \____/ \____\ \____\/`____ \ 
    \/_______/\/___/ \/____/\/____/`/___/> \
                                      /\___/
                                      \/__/ 
*/
```