# xian-yu

闲鱼相关工具安装包归档仓库。所有 `.exe` 通过 **Git LFS** 存储。

## 文件清单

| 文件名 | 大小 | SHA256 |
| --- | --- | --- |
| AgisoIdleClient_x64_1.2.5.exe | 90.8 MiB | `91058003852192af431b2c08461d435bb343fde311dfefa010dbce6382f9d36d` |
| celery-shop-manager-1.0.7-ip-setup.exe | 228.7 MiB | `e6ce5e1d88a38fe8ec18814579595dd206f76b822474b49cea33d0f35114555f` |
| kuaiyu-pro-setup-1.31.8.exe | 166.3 MiB | `3be7a4bc8863e02b33c7c39cb31788d411e93dccbe96afb59aed6b28fa228b48` |
| xianyu-dazi-vip-202608261840.exe | 35.1 MiB | `e89b9c6a3a6d09087edfeaa69a82ed844d6fdb2d156ff66b85eef57928efb19a` |
| 闲管家-闲鱼客服聊天_v1.21.91.exe | 84.0 MiB | `96d2fb3eb6efedf76857a4d755a0a73e1fbe2db27f319856e7eadd239cd2abb5` |
| 闲管家-闲鱼工作台_v1.3.4.exe | 74.3 MiB | `a06a2da8aa6bf4292916e29d6117fba23418882f7fff89148993373c1dfa3d75` |

合计约 683 MiB。

## 下载

克隆仓库后文件会自动由 LFS 还原：

```bash
git lfs install
git clone https://github.com/merelyer/xian-yu.git
```

仅需单个文件时，可直接访问仓库文件页的 Raw 地址下载。

## 校验

下载后可比对 SHA256，确认文件完整、未被篡改：

```bash
sha256sum -c SHA256SUMS      # Linux / macOS
certutil -hashfile <文件> SHA256   # Windows
```
