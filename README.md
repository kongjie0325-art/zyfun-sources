# 🎬 Zyfun 视频源 & 直播源合集

> 全面整合 GitHub 上可用的 Zyfun（原 ZY Player）视频解析源、直播源、IPTV 源、CMS 资源站、Alist 网盘源。
> **一键下载 JSON → 本地导入 Zyfun，搞定。**

[![GitHub stars](https://img.shields.io/github/stars/kongjie0325-art/zyfun-sources?style=social)](https://github.com/kongjie0325-art/zyfun-sources)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 🚀 一键导入（推荐）

### 方式一：下载 JSON → 本地导入（最稳定）

1. 点击下方链接下载 JSON 文件
2. 打开 Zyfun → 设置 → 基础配置 → 数据管理 → **本地导入** → 选择下载的 JSON 文件

📥 **完整版（解析 + 直播 + 央视卫视）**：
```
https://raw.githubusercontent.com/kongjie0325-art/zyfun-sources/main/zyfun-all-in-one.json
```

包含：17 个解析接口 + 11 个 IPTV 源 + 48 个直播频道

### 方式二：远端导入（可能因网络失败）

如果本地导入失败，可尝试远端导入同一链接：
```
https://raw.githubusercontent.com/kongjie0325-art/zyfun-sources/main/zyfun-all-in-one.json
```

> ⚠️ 提示：Zyfun 对 JSON 格式要求严格。如果远端导入失败，**请下载后本地导入**，100% 成功。

---

## 🎞️ CMS 资源站（单独添加）

> CMS 资源站不能通过 JSON 导入，需要**逐个手动添加**。
> 设置 → 基础配置 → 数据管理 → 快捷配置 → **此软件** → 填入以下 API 地址。

| 名称 | API 地址 |
|------|----------|
| 量子资源 | `http://cj.lziapi.com/api.php/provide/vod/` |
| 非凡资源 | `http://www.ffzy.tv/api.php/provide/vod/` |
| 快车资源 | `https://caiji.kuaichezy.org/api.php/provide/vod/?ac=list` |
| 无尽资源 | `https://api.wujinapi.me/api.php/provide/vod/` |
| 速播资源 | `https://subocj.com/api.php/provide/vod/at/json` |
| 魔爪资源 | `https://mozhuazy.com/api.php/provide/vod/at/xml` |
| 极速资源 | `https://jszyapi.com/api.php/provide/vod` |
| 樱花资源 | `https://m3u8.apiyhzy.com/api.php/provide/vod/` |
| 闪电资源 | `http://sdzyapi.com/api.php/provide/vod/` |
| 红牛资源 | `https://www.hongniuzy2.com/api.php/provide/vod/` |
| 旺旺资源 | `https://api.wwzy.tv/api.php/provide/vod/at/xml/?ac=list` |
| 猫眼资源 | `https://api.maoyanapi.top/api.php/provide/vod/at/xml` |
| 百度资源 | `https://api.apibdzy.com/api.php/provide/vod/?ac=list` |
| 暴风资源 | `https://bfzyapi.com/api.php/provide/vod/at/xml` |
| 光速资源 | `https://api.guangsuapi.com/api.php/provide/vod/at/xml/` |
| 牛牛资源 | `https://api.niuniuzy.me/api.php/provide/vod/from/nnm3u8/at/xml` |
| 细胞资源 | `https://www.xxibaozyw.com/api.php/provide/vod/at/xml/` |
| 电影天堂 | `http://caiji.dyttzyapi.com/api.php/provide/vod/at/xml/` |
| 虎牙资源 | `https://www.huyaapi.com/api.php/provide/vod/at/json` |
| 淘片资源 | `https://taopianapi.com/cjapi/sda/vod/json.html` |
| 金鹰云资源 | `https://jyzyapi.com/provide/vod/from/jinyingyun/at/json` |
| 豆瓣资源 | `https://caiji.dbzy5.com/api.php/provide/vod/at/josn/` |
| 茅台资源 | `https://caiji.maotaizy.cc/api.php/provide/vod/at/josn/` |
| 幸资源站 | `https://xzybb1.com/api.php/provide/vod/at/xml` |
| 猫眼资源2 | `https://api.maoyanapi.top/api.php/provide/vod` |
| CK伦理资源 | `https://ckzy.me/api.php/provide/vod/at/xml/?ac=list` |
| ikun资源 | `https://ikunzyapi.com/api.php/provide/vod/from/ikm3u8/at/json` |
| 金鹰资源 | `https://jyzyapi.com/provide/vod/at/xml/` |

---

## 📦 Alist 网盘源（单独添加）

> 数据管理 → 快捷配置 → 选择 **Alist** 类型 → 填入以下地址。

| 名称 | 地址 |
|------|------|
| 🙋 丫仙女 | `http://alist.xiaoya.pro/` |
| 🤮 布满灰尘 | `https://pan.baiblog.ren/` |
| 🌊 七米蓝 | `https://al.chirmyram.com` |
| 🌴 非盘 | `http://www.feifwp.top` |
| 🥼 帅盘 | `https://hi.shuaipeng.wang` |
| 🐉 神族九帝 | `https://alist.shenzjd.com` |
| ☃ 姬路白雪 | `https://pan.jlbx.xyz` |
| 🎧 听闻网盘 | `https://wangpan.sangxuesheng.com` |
| ✨ 星梦 | `https://pan.bashroot.top` |

---

## 🎬 解析接口一览

以下已包含在 `zyfun-all-in-one.json` 中：

| 名称 | 接口地址 | 类型 |
|------|----------|------|
| 咸鱼 | `https://jx.xyflv.cc/?url=` | 通用 |
| 虾米 | `https://jx.xmflv.com/?url=` | 通用 |
| 夜幕 | `https://www.yemu.xyz/?url=` | 通用 |
| M3U8.TV | `https://dmjx.m3u8.tv/?url=` | M3U8 |
| 冰豆 | `https://bd.jx.cn/?url=` | 通用 |
| CK | `https://www.ckplayer.vip/jiexi/?url=` | CKPlayer |
| PlayerJy | `https://jx.playerjy.com/?url=` | 需点击 |
| BL | `https://vip.bljiex.com/?v=` | VIP |
| 777Player | `https://jx.jsonplayer.com/player/?url=` | JSONPlayer |
| 爱狗 | `https://jx.i2g.cn/?url=` | 通用 |
| 南风蓝光 | `http://jx.66666zy.top/?url=` | 蓝光 |
| 猫影 | `https://jx.xgphp.cn/player/?url=` | 通用 |
| 1907 | `https://im1907.top/?jx=` | 需点击 |
| 爱豆 | `https://jx.aidouer.net/?url=` | 通用 |
| OK解析 | `https://okjx.cc/?url=` | 通用 |
| 诺讯 | `https://www.nxflv.com/?url=` | 通用 |
| 人人迷 | `https://jx.blbo.cc:4433/?url=` | 通用 |

---

## 📺 直播源 / IPTV

以下已包含在 `zyfun-all-in-one.json` 中：

| 名称 | 链接 |
|------|------|
| APTV | `https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u` |
| 4K/8K | `https://raw.githubusercontent.com/Ftindy/IPTV-URL/main/IPTV.m3u` |
| 秋天直播 | `https://pan.shangui.cc/f/XR6dud/秋天直播.txt` |
| 电视伴音(广播) | `https://mirror.ghproxy.com/https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/radio.m3u` |
| pastebin | `https://pastebin.com/raw/tuXBQs7U` |
| 大杂烩 | `https://mirror.ghproxy.com/https://raw.githubusercontent.com/rad168/iptv/main/live.m3u` |
| 秒看电视 | `https://pan.shangui.cc/f/w7Y4fg/电视家.txt` |
| 天微科技 | `https://tvkj.top/tvlive.txt` |
| 广播 | `https://mirror.ghproxy.com/https://raw.githubusercontent.com/YueChan/Live/main/Radio.m3u` |
| vbskycn IPTV4 | `https://gh-proxy.com/raw.githubusercontent.com/vbskycn/iptv/refs/heads/master/tv/iptv4.txt` |
| vbskycn IPTV6 | `https://gh-proxy.com/raw.githubusercontent.com/vbskycn/iptv/refs/heads/master/tv/iptv6.txt` |

---

## 📖 导入步骤详解

### 本地导入（推荐）

```
1. 浏览器打开 → https://raw.githubusercontent.com/kongjie0325-art/zyfun-sources/main/zyfun-all-in-one.json
2. 右键 → 另存为 → zyfun-all-in-one.json
3. 打开 Zyfun → 右上角 ⚙️ Settings
4. 基础配置 → 数据管理 → 数据导入 → 本地导入
5. 选择 zyfun-all-in-one.json → 导入
6. 刷新或重启
```

### 远端导入

```
1. 打开 Zyfun → 右上角 ⚙️ Settings
2. 基础配置 → 数据管理 → 数据导入 → 远端导入
3. 填入：https://raw.githubusercontent.com/kongjie0325-art/zyfun-sources/main/zyfun-all-in-one.json
4. 点击导入 → 刷新或重启
```

### CMS 资源站添加

```
1. 设置 → 基础配置 → 数据管理 → 快捷配置
2. 选择 "此软件" → 填入 API 地址（如 量子资源）
3. 点击保存 → 重复添加其他 CMS 源
```

---

## 🔗 相关链接

- [Zyfun 官方 GitHub](https://github.com/Hiram-Wong/zyfun) — Zyfun 播放器
- [chao921125/source](https://github.com/chao921125/source) — 最全面的第三方源
- [vbskycn/iptv](https://github.com/vbskycn/iptv) — 自动更新 IPTV 源
- [hjdhnx/dr_py](https://github.com/hjdhnx/dr_py) — Drpy 官方源码

---

## 📜 License

MIT License — 本项目仅收集公开源链接，不存储任何媒体内容。
