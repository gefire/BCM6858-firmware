## 说明

### 来源
  根据gihub: ( https://github.com/weihutaisui/BCM ) 编译的固件

### 适配
目前测试:
   nokia xs-020x-a
   nokia u-090cp-p
   可刷
### 刷机方式
   注意： 由于没有相关官方固件，刷机后无法返回，请自行备份官方固件
   TTL 进入CFE ，然后通过CFE web上传固件刷机即可
   ！！！！！请刷写2次以上！！！！


### 问题
   泄露SDK，功能未经测试
   根据SDK内容，支持XGSPON/XGPON/GPON/EPON/10G EPON ,但是不支持国内电信GPON相关扩展，所以不能认证，如果是SN认证可以尝试 EPON 及10G EPON 有 loid ploam ，但均未经测试。
   