一键导出京东校园版电子书（epub 格式）

![](./preview.png)

## 如何使用

第一步，下载代码, 安装依赖：

```shell
git clone https://github.com/UltramarineSky/export-jd-xy-read.git
cd export-jd-xy-read
npm i
npm run start
```

第二步，登录 gx.jd.com 登录状态下，复制 cookie 中的 `_gx_ght_u_` 到 `config.js` 中的 `gx` 变量；

第三步，随便找一本书, 右键查看源代码，搜索 `tob=` 的值到 `config.js` 中的 `tob` 变量；

第四步，执行 `npm run start` 后，输入图书 URL 中的 `bookId` 即可，如果图书中的图片较多，可能需要花费一些时间。

## 说明

此脚本不会收集您的 cookie 信息，请放心使用。
