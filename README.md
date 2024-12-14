# Hysteria 2 一键安装脚本

支持多种操作系统和架构，尤其推荐 Debian/Ubuntu 系统。脚本同时支持域名用户通过 ACME 申请证书，以及无域名用户使用自签名证书。

### **特性:**

* **一键安装:**  自动化安装 Hysteria 2 服务器端。
* **跨平台支持:** 兼容大部分主流操作系统和架构，包括纯 IPv4 和纯 IPv6 环境。
* **证书灵活:**  支持使用域名通过 ACME 自动申请 Let's Encrypt 证书，也支持生成自签名证书。
* **内核优化 (可选):** 可选安装 Xanmod 内核并启用 BBRv3 加速，提升网络性能。(基于 [ylx2016 的脚本](https://github.com/ylx2016/Linux-NetSpeed))
* **深度 Nekobox 适配:**  与 Nekobox 客户端高度兼容，尤其在端口跳跃场景下表现出色。


## **安装步骤:**

在服务器终端执行以下命令:

```bash
curl -sSL https://github.com/sdgaaerdt/hysteria2-clean/raw/main/install.sh -o install.sh && chmod +x install.sh && bash install.sh
```

## **客户端推荐:**

本脚本安装的 Hysteria 2 服务器需要配合支持 Hysteria 2 协议的客户端使用。以下列出一些推荐的客户端：

* **iOS:**
    * [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118)

* **Android:**
    * [NekoBox](https://github.com/MatsuriDayo/NekoBoxForAndroid)
    * [Clash Meta](https://github.com/MetaCubeX/ClashMetaForAndroid)
    * [Hiddify](https://github.com/hiddify/hiddify-next)

* **桌面端 (Windows, macOS, Linux):**
    * [Nekoray](https://github.com/MatsuriDayo/nekoray)
    * [Clash Verge](https://github.com/clash-verge-rev/clash-verge-rev)
    * [Hiddify](https://github.com/hiddify/hiddify-next)


## **客户端配置及 Cloudflare 令牌:**

关于客户端的具体配置方法，以及如何获取 Cloudflare API 令牌 (如果需要)，请参考以下官方文档：

* Hysteria 2 客户端配置: [https://v2.hysteria.network/zh/docs/getting-started/Client/](https://v2.hysteria.network/zh/docs/getting-started/Client/)
* Cloudflare API 令牌: [https://dash.cloudflare.com/profile/api-tokens](https://dash.cloudflare.com/profile/api-tokens)


## **项目地址:**

* 本一键安装脚本: [https://github.com/sdgaaerdt/hysteria2-clean](https://github.com/sdgaaerdt/hysteria2-clean)
* Hysteria 2 项目: [https://github.com/apernet/hysteria](https://github.com/apernet/hysteria)


## **免责声明:**

本脚本及其相关资源仅供学习和研究用途，不得用于任何非法活动或商业目的。请在下载后 24 小时内删除。使用本脚本，即表示您同意遵守所有适用的法律法规，并承担所有责任。作者不对任何因使用本脚本而造成的直接或间接损失负责。 使用前请确保您了解并遵守您所在国家/地区的相关法律法规。
