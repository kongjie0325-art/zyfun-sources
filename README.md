# 🎬 Zyfun 视频源 & 直播源合集

> 全面收集 GitHub 上可用的 Zyfun（原 ZY Player）视频解析源、直播源、IPTV 源，分类整理，一键导入。

[![GitHub stars](https://img.shields.io/github/stars/kongjie0325-art/zyfun-sources?style=social)](https://github.com/kongjie0325-art/zyfun-sources)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Updated](https://img.shields.io/badge/updated-2026--06--06-brightgreen.svg)](https://github.com/kongjie0325-art/zyfun-sources/commits/main)

## 📋 目录

- [快速导入](#快速导入)
- [视频解析源（远端导入）](#视频解析源远端导入)
- [直播源 / IPTV](#直播源--iptv)
- [一站式源合集](#一站式源合集)
- [Drpy 自定义源](#drpy-自定义源)
- [失效源记录](#失效源记录)
- [如何贡献](#如何贡献)

---

## ⚡ 快速导入

打开 Zyfun → 设置 → 基础配置 → 数据管理 → **远端导入** → 粘贴以下任一链接：

### 🥇 推荐：chao921125/source（最全面，30+ 解析接口 + 直播源）

```
https://raw.githubusercontent.com/chao921125/source/main/zyfun/index.json
```

包含：咸鱼、虾米、夜幕、M3U8.TV、冰豆、CK、BL、诺讯、人人迷等 30+ 解析接口 + IPTV 直播源。

### 🥈 备选：ls125781003/dmtg（知乎推荐，精简版）

```
https://cdn.jsdmirror.cn/gh/ls125781003/dmtg@master/zy.json
```

### 🥉 备选：念心分享源

```
https://pz.nxpz.xyz/nx.json
```

---

## 🎬 视频解析源（远端导入）

### 综合解析源

| 名称 | 导入链接 | 说明 |
|------|----------|------|
| **chao921125/source** ⭐ | [raw](https://raw.githubusercontent.com/chao921125/source/main/zyfun/index.json) | 30+ 解析接口，最全面 |
| **ls125781003/dmtg** | [mirror](https://cdn.jsdmirror.cn/gh/ls125781003/dmtg@master/zy.json) | 知乎推荐，精简稳定 |
| **念心** | [link](https://pz.nxpz.xyz/nx.json) | 念心分享源 |
| **cuiocean** | [mirror](https://cdn.jsdelivr.net/gh/cuiocean/ZY-Player-Resources@main/Recommendations/Recommendations.json) | ZY Player 资源推荐 |

### 单解析接口（Drpy JS）

| 名称 | 接口地址 | 类型 |
|------|----------|------|
| 咸鱼 | `https://jx.xyflv.cc/?url=` | 通用解析 |
| 虾米 | `https://jx.xmflv.com/?url=` | 通用解析 |
| 夜幕 | `https://www.yemu.xyz/?url=` | 通用解析 |
| M3U8.TV | `https://dmjx.m3u8.tv/?url=` | M3U8 解析 |
| 冰豆 | `https://bd.jx.cn/?url=` | 通用解析 |
| CK | `https://www.ckplayer.vip/jiexi/?url=` | CKPlayer |
| PlayerJy | `https://jx.playerjy.com/?url=` | 需点击 |
| BL | `https://vip.bljiex.com/?v=` | VIP 解析 |
| 777Player | `https://jx.jsonplayer.com/player/?url=` | JSONPlayer |
| 爱狗 | `https://jx.i2g.cn/?url=` | 通用解析 |
| 南风蓝光 | `http://jx.66666zy.top/?url=` | 蓝光解析 |
| 猫影 | `https://jx.xgphp.cn/player/?url=` | 通用解析 |
| 1907 | `https://im1907.top/?jx=` | 需点击 |
| 爱豆 | `https://jx.aidouer.net/?url=` | 通用解析 |
| OK解析 | `https://okjx.cc/?url=` | 通用解析 |
| 诺讯 | `https://www.nxflv.com/?url=` | 通用解析 |
| 人人迷 | `https://jx.blbo.cc:4433/?url=` | 通用解析 |

---

## 📺 直播源 / IPTV

### 国内 IPTV 源（M3U/TXT）

| 名称 | 链接 | 说明 |
|------|------|------|
| **vbskycn/iptv** ⭐ | [IPTV4](https://gh-proxy.com/raw.githubusercontent.com/vbskycn/iptv/refs/heads/master/tv/iptv4.txt) | 自动更新，IPv4/IPv6 双栈 |
| **vbskycn/iptv (IPv6)** | [IPTV6](https://gh-proxy.com/raw.githubusercontent.com/vbskycn/iptv/refs/heads/master/tv/iptv6.txt) | IPv6 专用 |
| **dongyubin/IPTV** | [GitHub](https://github.com/dongyubin/IPTV) | 2026 世界杯、体育直播 |
| **suxuang/myIPTV** | [GitHub](https://github.com/suxuang/myIPTV) | 典藏版，高清卫视 |
| **ngo5/IPTV** | [GitHub](https://github.com/ngo5/IPTV) | IPV4/IPV6 双栈 |

### 直播源（GitHub 项目）

| 项目 | 链接 | Stars | 说明 |
|------|------|-------|------|
| **vbskycn/iptv** | [GitHub](https://github.com/vbskycn/iptv) | 3.5k+ | 每 6 小时自动更新 |
| **dongyubin/IPTV** | [GitHub](https://github.com/dongyubin/IPTV) | 247 commits | 体育/F1 直播 |
| **suxuang/myIPTV** | [GitHub](https://github.com/suxuang/myIPTV) | - | 手工维护，高清 |
| **ngo5/IPTV** | [GitHub](https://github.com/ngo5/IPTV) | - | 自动收集 |
| **fanmingming/live** | [GitHub](https://github.com/fanmingming/live) | 18k+ | IPTV 播放器 + 源 |

### 直播源（直接 M3U 链接）

| 名称 | 链接 |
|------|------|
| APTV | `https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u` |
| 4K/8K | `https://raw.githubusercontent.com/Ftindy/IPTV-URL/main/IPTV.m3u` |
| 秋天直播 | `https://pan.shangui.cc/f/XR6dud/秋天直播.txt` |
| 电视伴音(广播) | `https://mirror.ghproxy.com/https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/radio.m3u` |
| 大杂烩 | `https://mirror.ghproxy.com/https://raw.githubusercontent.com/rad168/iptv/main/live.m3u` |
| 秒看电视 | `https://pan.shangui.cc/f/w7Y4fg/电视家.txt` |
| 天微科技 | `https://tvkj.top/tvlive.txt` |
| 广播 | `https://mirror.ghproxy.com/https://raw.githubusercontent.com/YueChan/Live/main/Radio.m3u` |

---

## 🎯 一站式源合集（推荐）

以下源包含视频解析 + 直播 + EPG，一次导入全部搞定：

| 名称 | 链接 | 说明 |
|------|------|------|
| **chao921125/source** ⭐ | [raw](https://raw.githubusercontent.com/chao921125/source/main/zyfun/index.json) | 最全面，30+ 接口 |
| **ls125781003/dmtg** | [mirror](https://cdn.jsdmirror.cn/gh/ls125781003/dmtg@master/zy.json) | 精简稳定 |
| **念心** | [link](https://pz.nxpz.xyz/nx.json) | 轻量 |
| **xiaoguozitv** | [link](http://xiaoguozitv.cn/catys/zyplay.json) | - |
| **heimuer** | [link](https://json02.heimuer.xyz/api.php/provide/vod) | CMS 资源 |
| **bfzyapi** | [link](https://bfzyapi.com/api.php/provide/vod) | CMS 资源 |

---

## 🔧 Drpy 自定义源

Zyfun 支持 Drpy（影视仓）格式的 JS 源。以下 GitHub 仓库提供 Drpy 源：

| 项目 | 链接 | 说明 |
|------|------|------|
| **chao921125/source/drpy_dz** | [GitHub](https://github.com/chao921125/source/tree/main/zyfun/drpy_dz) | 定制 Drpy 源 |
| **chao921125/source/drpy_dzlive** | [GitHub](https://github.com/chao921125/source/tree/main/zyfun/drpy_dzlive) | Drpy 直播源 |
| **chao921125/source/drpy_gao** | [GitHub](https://github.com/chao921125/source/tree/main/zyfun/drpy_gao) | 高赞 Drpy 源 |
| **hjdhnx/dr_py** | [GitHub](https://github.com/hjdhnx/dr_py) | Drpy 官方源码，含大量 JS 源 |

### Drpy 单 JS 源（可在 Zyfun 中直接填入接口地址）

| 名称 | 接口地址 |
|------|----------|
| cokemv | `https://cdn.jsdelivr.net/gh/hjdhnx/dr_py@main/js/cokemv.js` |
| 更多 Drpy JS 源 | [dr_py 仓库](https://github.com/hjdhnx/dr_py/tree/main/js) |

---

## ❌ 失效源记录

以下源已确认失效，仅供参考：

| 名称 | 原链接 | 失效原因 |
|------|--------|----------|
| 原动力在线 CMS | - | 2024.7.17 域名到期 |
| 100km.top/Ray | `https://100km.top/0` | 重定向问题 |
| 吃猫的鱼 | `https://kstore.dev/download/7213/吃猫的鱼` | 需登录 |

---

## 📖 如何贡献

欢迎提交 PR 或 Issue 分享你发现的可用源！

### 贡献指南

1. Fork 本仓库
2. 创建分支 (`git checkout -b add/source-name`)
3. 在对应分类下添加源链接
4. 提交 PR

### 添加格式

```markdown
| **源名称** | [链接](https://raw.githubusercontent.com/xxx/xxx/main/xxx.json) | 简要说明 |
```

请确保：
- 源链接可以正常访问
- 标注源的类型（视频/直播/综合）
- 如已知最后更新时间，请标注

---

## 🔗 相关链接

- [Zyfun 官方 GitHub](https://github.com/Hiram-Wong/zyfun) - Zyfun 播放器
- [ZY Player 旧版](https://github.com/Hunlongyu/ZY-Player) - 前身项目
- [chao921125/source](https://github.com/chao921125/source) - 最全面的源
- [vbskycn/iptv](https://github.com/vbskycn/iptv) - 自动更新 IPTV 源

---

## 📜 License

MIT License - 本项目仅收集公开源链接，不存储任何媒体内容。
