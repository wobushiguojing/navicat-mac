# navicat-mac
原文链接 https://zhuanlan.zhihu.com/p/108692959

Navicat 15 keygen for Mac 安装教程
狼烟四起
狼烟四起
6毛硬币
2 人赞同了该文章
原文链接：Navicat 15 keygen for Mac 安装教程

Navicat 15 keygen for Mac 安装教程

(出处: 吾爱破解论坛)

2020-02-29 更新我备份的网盘链接如下：

下载地址：链接:https://pan.baidu.com/s/1CwQQT_xZstnzWbcR4cfwtg 密码:s55q

把原文内容贴在这里以做备份

介绍
Navicat Premium 是一套数据库开发管理工具，支持连接 MySQL、Oracle等多种数据库，可以快速轻松地创建、管理和维护数据库
准备

备份好之前安装过的 Navicat 中所有已保存的数据库连接(包括密码)
移除所有 Navicat 在 钥匙串访问 中保存的连接，如果有的话。您可以通过在 钥匙串访问 中搜索关键词 navicat 来找到它们
安装

下载 navicat150_premium_cs.dmg 后打开并将 Navicat Premium 拖放到 /Application (即 应用程序) 中
通过如下命令，使用 navicat-patcher 替换掉公钥
./navicat-patcher /Applications/Navicat\ Premium.app/



生成一份自签名的代码证书，并总是信任该证书。这一步非常重要
打开 “钥匙串访问”，选择菜单栏的 钥匙串访问->证书助理->创建证书，然后证书类型选择 “代码签名”。



然后在证书上右键选择“显示简介”，在“使用证书”那里选择始终信任。

用codesign对libcc-premium.dylib（如果有的话） 和Navicat Premium.app重签名。
如果你的Navicat Premium版本号高于15.0.0，
你必须先签名libcc-premium.dylib，再签名Navicat Premium.app。codesign -f -s Navicat /Applications/Navicat\ Premium.app/Contents/Frameworks/libcc-premium.dylib codesign -f -s Navicat /Applications/Navicat\ Premium.app/


接下来使用 navicat-keygen 来生成 序列号 和 激活码。
./navicat-keygen ./RegPrivateKey.pem
依次选择 1 --- 15 之后你会被要求填入请求码。注意 不要关闭注册机。



断开网络 并打开 Navicat
找到注册窗口，填入注册机给你的序列号。然后点击激活按钮。
一般来说在线激活肯定会失败，这时候Navicat会询问你是否手动激活，直接选吧。
在手动激活窗口你会得到一个请求码，复制它并把它粘贴到keygen里。最后别忘了连按至少两下回车结束输入。



如果不出意外，你会得到一个看似用Base64编码的激活码。
直接复制它，并把它粘贴到Navicat的手动激活窗口，最后点激活按钮。
如果没什么意外的话应该能成功激活。
