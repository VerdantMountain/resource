## 矿龙：网维大师客户机无法同步挖矿程序的解决方法：

- 可能原因：网维大师的服务端没有进行程序更新，可按照以下步骤操作。
- 解决步骤(1)：重新生成一次开机程序，然后关闭客户机

  <img src="https://github.com/qingshan2048/resource/blob/main/wangweidashi1.jpg">
- 解决步骤(2)：等开机程序状态显示更新完成，打开客户机

  <img src="https://github.com/qingshan2048/resource/blob/main/wangweidashi2.jpg">

## 币策：系统提示无法找到 VCRUNTIME140.DLL，MSVCP140.DLL，VCRUNTIME140_1.DLL 的解决方法：

- 提示：“由于找不到 VCRUNTIME140.DLL，MSVCP140.DLL，VCRUNTIME140_1.DLL，无法继续执行代码。重新安装程序可能会解决此问题。”，如在阿里云的轻量服务器中 (Windows 2022数据中心版) 系统镜像中会出现此问题
- 解决步骤(1)：下载文件
```bash
VCRUNTIME140.DLL: https://github.com/qingshan2048/resource/raw/main/vcruntime140.dll
MSVCP140.DLL: https://github.com/qingshan2048/resource/raw/main/msvcp140.dll
VCRUNTIME140_1.DLL: https://github.com/qingshan2048/resource/raw/main/vcruntime140_1.dll
```

- 解决步骤(2)：将文件解压到币策相同目录后运行币策即可
