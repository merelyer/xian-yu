# xian-yu

闲鱼生态第三方工具安装包归档仓库。所有 `.exe` / `.zip` 均通过 **Git LFS** 存储，按厂商分类存放于 `安装包/` 目录下。

## 目录结构

```
安装包/
├── 阿奇索-鱼店长/      发货 / 工作台
├── 闲管家/             客服聊天 / 工作台
├── 芹菜-店铺管理/      店铺管理
├── 闲鱼搭子/           选品
├── 快鱼Pro/            选品 / 运营
└── 甩手工具箱/         综合工具箱
```

## 文件清单

### 阿奇索 · 鱼店长（发货 / 工作台）

| 文件 | 大小 | SHA256 |
| --- | --- | --- |
| AgisoIdleClient_x64_1.2.5.exe | 90.8 MiB | `91058003852192af431b2c08461d435bb343fde311dfefa010dbce6382f9d36d` |

### 闲管家（客服 / 工作台）

| 文件 | 大小 | SHA256 |
| --- | --- | --- |
| 闲管家-闲鱼客服聊天_v1.21.91.exe | 84.0 MiB | `96d2fb3eb6efedf76857a4d755a0a73e1fbe2db27f319856e7eadd239cd2abb5` |
| 闲管家-闲鱼工作台_v1.3.4.exe | 74.3 MiB | `a06a2da8aa6bf4292916e29d6117fba23418882f7fff89148993373c1dfa3d75` |

### 芹菜 · 店铺管理

| 文件 | 大小 | SHA256 |
| --- | --- | --- |
| celery-shop-manager-1.0.7-ip-setup.exe | 228.7 MiB | `e6ce5e1d88a38fe8ec18814579595dd206f76b822474b49cea33d0f35114555f` |

### 闲鱼搭子（选品）

| 文件 | 大小 | SHA256 |
| --- | --- | --- |
| xianyu-dazi-vip-202608261840.exe | 35.1 MiB | `e89b9c6a3a6d09087edfeaa69a82ed844d6fdb2d156ff66b85eef57928efb19a` |

### 快鱼 Pro（选品 / 运营）

| 文件 | 大小 | SHA256 |
| --- | --- | --- |
| kuaiyu-pro-setup-1.31.8.exe | 166.3 MiB | `3be7a4bc8863e02b33c7c39cb31788d411e93dccbe96afb59aed6b28fa228b48` |

### 甩手工具箱（综合）

| 文件 | 大小 | SHA256 |
| --- | --- | --- |
| SszgToolBoxSetupBeta5_fw_5.77.00.exe.zip | 164.0 MiB | `9dca9ca49dd931494febc6832f9ff8a2db84de920364f08fb902707f46f17a8a` |

**合计 7 个文件，约 843.2 MiB。**

## 下载

克隆仓库后 LFS 文件会自动还原：

```bash
git lfs install
git clone https://github.com/merelyer/xian-yu.git
```

只需单个文件时，可在仓库文件页打开对应路径后点击 Raw 下载。

## 校验

```bash
sha256sum -c SHA256SUMS                    # Linux / macOS
certutil -hashfile <文件名> SHA256          # Windows
```

## 说明

- 本仓库仅作**安装包版本归档**，所有文件版权归各原厂商所有，不含任何破解、修改或反编译产物。
- 仓库已启用 Git LFS。当前占用约 843 MiB，GitHub 免费额度为 1 GiB 存储 / 1 GiB 月流量，**剩余空间有限，新增大型安装包前请预留余量**。
- 增加新文件时请按厂商归入对应子目录，并同步更新 `SHA256SUMS` 与本清单。
