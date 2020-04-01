# recipient-address-splitter-js
收件人地址自动分离

## 介绍
从带有地址、姓名、手机号的字符串中，分离出省、市、县、区、姓名、手机号等信息，例如：

```张三13508348543 北京市北京市东城区前门大街1号```

```四川省成都市双流县幸福社区23号 李四13512345678```

```王五 福建省福州市福清市融城镇龙山街道塔北巷18号 18512345678```

```四川省成都市都江堰市天马镇34号13912345678刘六七```

## 使用方法
将```recipient-address-splitter.js```拷贝至你的项目中，在html文件中加入：

```
<script src="js/address-splitter.js"></script>
<script>
  ...
  addr = RecipientAddressSplitter('张三13508348543 北京市北京市东城区前门大街1号')
  console.log(addr[0],addr[1],addr[2],addr[3],addr[4],addr[5],addr[6])
  ...
</script>
```
