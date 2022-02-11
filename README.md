# tnpm

![image](https://cloud.githubusercontent.com/assets/1147375/11032640/07affbbc-8718-11e5-8586-b5d040570c0f.png)

目前在国内前端领域，tnpm 有 2 个含义：

- 阿里巴巴及蚂蚁集团 企业私有 NPM 服务。（起源为 taobao npm）
- 腾讯 企业私有 NPM 服务。（tencent npm）

但它们均为企业服务，只能通过各自内网进行安装。

为了避免企业新用户不小心通过 `npm install tnpm` 安装了错误的 `tnpm`，故该包作为占位包，在安装时给出友情提示。
