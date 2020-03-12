配置文件集合
1、不折腾版本，类小火箭体验，文件：default_lazy_select.conf
国内直连
常见广告域名屏蔽
支持访问常见国外网站
电报 telegram 支持
抗 DNS 污染

2、分组折腾版，文件：default_king_select.conf
增加 NobyDa 去广告规则
ACL4SSR 去广告规则
网易云解锁规则
所有规则引用远程规则
Rewrite 引用本地

！！注意配置中带了 CA 证书，若需要 MITM 和 Rewrite 功能有效，请到配置->证书管理中先信任证书。

3、分组清爽版，文件：default_honjow.conf
配置清爽，方便修改
精简策略组
复写规则采用神机规则

！！注意配置中带了 CA 证书，若需要 MITM 和 Rewrite 功能有效，请到配置->证书管理中先信任证书
