# NsSubDomainBurst

# 1. 简介
一个实现DNS爆破的库

参考文章：https://www.birdy02.com/2024/10/14/20561f85-40a8-4cb0-9f46-705eb2aae562
```
>> python onlySubDomain.py
>> [*] 请输入域名: birdy02.com
```
* 内置了多个DNS服务器
* 内置子域名：76136个
* 只支持A记录
# 2. 运行
```
[*] 请输入域名: birdy02.com
[2024-11-25 12:31:01] INFO: DNS subDomain: birdy02.com
[2024-11-25 12:31:32] INFO: DNS: oss.birdy02.com => 38.147.170.156
[2024-11-25 12:31:36] INFO: DNS: tools.birdy02.com => 38.147.170.156
[2024-11-25 12:31:40] INFO: DNS: home.birdy02.com => 10.16.3.1
[2024-11-25 12:31:40] INFO: DNS: l.birdy02.com => 127.0.0.1
[2024-11-25 12:31:45] INFO: DNS: dash.birdy02.com => 38.147.170.156
[2024-11-25 12:31:50] INFO: DNS: docs.birdy02.com => 38.147.170.156
[2024-11-25 12:31:50] INFO: DNS: w.birdy02.com => 38.147.170.156
[2024-11-25 12:31:54] INFO: DNS: bt.birdy02.com => 38.147.170.156
[2024-11-25 12:31:55] INFO: DNS: doc.birdy02.com => 38.147.170.156
[2024-11-25 12:31:55] INFO: DNS: doc-api.birdy02.com => 38.147.170.156
[2024-11-25 12:31:59] INFO: DNS: api.birdy02.com => 38.147.170.156
[2024-11-25 12:36:37] INFO: DNS: www.birdy02.com => 38.147.170.156
[2024-11-25 12:40:16] INFO: [*] DnsDomain 耗时 532.9486651420593
```

会输出xlsx记录在output_zcsj目录下
