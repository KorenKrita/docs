---
# This is the icon of the page
icon: speed
# This control sidebar order
order: 7
# A page can have multiple categories
category:
  - Guide
# A page can have multiple tags
tag:
  - Advanced
  - Guide
# this page is sticky in article list
sticky: true
# this page will appear in starred articles
star: true
---

# 负载均衡

要求两个存储中的文件结构完全相同，程序会自动轮询所有存储进行下载/请求。

### 如何使用​

一个storage可以正常添加，另外一个storage可以以`第一个个storage 挂载路径 + .balance +任何其他内容`为挂载路径添加。
例如：

- 存储1：测试
- 存储 2：test.balance1
- 存储 3：test.balance2
- 存储 4：test.balance3
- ...
- 存储 n：test.balancen
