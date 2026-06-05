# 🎬 Zyfun / TVBox 视频源 & 直播源合集

> 全面整理自 GitHub 社区、知乎、CSDN、B站等平台的 Zyfun / TVBox 可用视频源。
> 分类清晰，支持一键导入，持续更新。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/kongjie0325-art/zyfun-sources?style=social)](https://github.com/kongjie0325-art/zyfun-sources)
[![Updated](https://img.shields.io/badge/updated-2026--06--06-brightgreen.svg)](https://github.com/kongjie0325-art/zyfun-sources/commits/master)

---

## 📋 目录

- [快速导入](#快速导入)
- [源分类说明](#源分类说明)
- [一、解析接口（analyze）](#一解析接口analyze)
- [二、CMS 资源站（cms）](#二cms-资源站cms)
- [三、直播源 / IPTV（live）](#三直播源--iptv-live)
- [四、云盘源 / Alist（cloud）](#四云盘源--alist-cloud)
- [五、drpy 源（drpy）](#五drpy-源drpy)
- [六、TVBox 兼容源（tvbox）](#六tvbox-兼容源tvbox)
- [七、一站式源合集](#七一站式源合集)
- [推荐订阅链接汇总](#推荐订阅链接汇总)
- [Zyfun 客户端下载](#zyfun-客户端下载)
- [注意事项](#注意事项)
- [更新记录](#更新记录)
- [免责声明](#免责声明)

---

## ⚡ 快速导入

### Zyfun 导入方式

1. 打开 Zyfun → 设置 → 基础配置 → 数据管理 → 配置导入
2. 选择 **远端导入**，粘贴下方订阅链接
3. 点击导入，然后 **刷新** 或 **重启软件**

### TVBox 导入方式

1. 打开 TVBox → 设置 → 配置地址
2. 粘贴下方订阅链接
3. 确定保存，返回首页自动加载

---

## 📂 源分类说明

| 分类 | 目录 | 说明 |
|------|------|------|
| 解析接口 | `sources/analyze/` | 视频解析/播放接口（咸鱼、虾米、夜幕等 35+） |
| CMS 资源站 | `sources/analyze/` | CMS 影视资源站 API（量子、非凡、红牛等 28+） |
| 直播源 | `sources/live/` | IPTV 直播源（m3u/m3u8，含 EPG） |
| 云盘源 | `sources/cloud/` | 网盘资源（Alist 等） |
| drpy 源 | `sources/drpy/` | drpy 格式的 JS 源 |
| TVBox 兼容 | `sources/tvbox/` | TVBox 格式的配置文件和订阅链接 |

---

## 一、解析接口（analyze）

> 解析接口用于播放在线视频，通过 URL 解析获取真实视频流。

### 1.1 综合解析源（推荐）

| 名称 | 链接 | 说明 |
|------|------|------|
| ⭐ chao921125/source | [raw](https://raw.githubusercontent.com/chao921125/source/main/zyfun/index.json) | 最全面，含 30+ 解析 + 28+ CMS + 直播 + 云盘 |
| ls125781003/dmtg | [raw](https://raw.githubusercontent.com/ls125781003/dmtg/main/zy_yuan.json) | 知乎推荐 |
| 念心分享源 | [链接](https://pz.nxpz.xyz/nx.json) | 精简版 |

### 1.2 独立解析接口列表

以下接口可直接在 Zyfun/TVBox 中添加为解析源：

| 名称 | 接口地址 | 类型 |
|------|----------|------|
| 咸鱼 | `https://jx.xyflv.cc/?url=` | 1 |
| 虾米 | `https://jx.xmflv.com/?url=` | 1 |
| 夜幕 | `https://www.yemu.xyz/?url=` | 1 |
| M3U8.TV | `https://dmjx.m3u8.tv/?url=` | 1 |
| 冰豆 | `https://bd.jx.cn/?url=` | 1 |
| CK | `https://www.ckplayer.vip/jiexi/?url=` | 1 |
| PlayerJy | `https://jx.playerjy.com/?url=` | 1 |
| BL | `https://vip.bljiex.com/?v=` | 1 |
| 777Player | `https://jx.jsonplayer.com/player/?url=` | 1 |
| 爱狗 | `https://jx.i2g.cn/?url=` | 1 |
| 南风蓝光 | `http://jx.66666zy.top/?url=` | 1 |
| 猫影 | `https://jx.xgphp.cn/player/?url=` | 1 |
| 1907 | `https://im1907.top/?jx=` | 1 |
| 爱豆 | `https://jx.aidouer.net/?url=` | 2 |
| OK解析 | `https://okjx.cc/?url=` | 2 |
| 诺讯 | `https://www.nxflv.com/?url=` | 2 |
| 人人迷 | `https://jx.blbo.cc:4433/?url=` | 2 |
| 七哥 | `https://jx.nnxv.cn/tv.php?url=` | 2 |
| 迪奥 | `https://123.1dior.cn/?url=` | 2 |
| ckmov | `https://www.ckmov.vip/api.php?url=` | 2 |
| H8 | `https://www.h8jx.com/jiexi.php?url=` | 2 |
| 解析la | `https://api.jiexi.la/?url=` | 2 |
| MUTV | `https://jiexi.janan.net/jiexi/?url=` | 2 |
| MAO | `https://www.mtosz.com/m3u8.php?url=` | 2 |
| 盘古 | `https://www.pangujiexi.cc/jiexi.php?url=` | 2 |
| 0523 | `https://go.yh0523.cn/y.cy?url=` | 2 |
| 17云 | `https://www.1717yun.com/jx/ty.php?url=` | 2 |
| 4K | `https://jx.4kdv.com/?url=` | 2 |
| 8090 | `https://www.8090g.cn/?url=` | 2 |
| 180 | `https://jx.000180.top/jx/?url=` | 2 |
| 无名 | `https://www.administratorw.com/video.php?url=` | 2 |
| yangtu | `https://jx.yangtu.top/?url=` | 2 |
| 小新 | `http://xiaoxin.1080p.me/api/?key=368b2df76af1b58d897bbe31a00180c0&url=` | 2 |
| 777 | `https://jx.777jiexi.com/player/?url=` | 2 |
| json | `https://jx.bozrc.com:4433/player/?url=` | 2 |
| 战狼 | `https://jx.zhanlangbu.com/?url=` | 2 |
| 听乐 | `https://jx.dj6u.com/?url=` | 2 |

> 类型 1 = 直接拼接 URL，类型 2 = 需通过 API 调用

---

## 二、CMS 资源站（cms）

> CMS 资源站提供影视内容的搜索和播放，支持分类筛选。
> Zyfun 3.3.4+ 支持 "一键配置 → 此软件" 类型填入 API 地址。

| 名称 | API 地址 | 搜索 | 说明 |
|------|----------|------|------|
| ⭐ 量子资源 | `http://cj.lziapi.com/api.php/provide/vod/` | ❌ | 稳定，内容丰富 |
| ⭐ 非凡资源 | `http://www.ffzy.tv/api.php/provide/vod/` | ❌ | 更新快 |
| ⭐ 快车资源 | `https://caiji.kuaichezy.org/api.php/provide/vod/?ac=list` | ✅ | 支持搜索 |
| ⭐ 无尽资源 | `https://api.wujinapi.me/api.php/provide/vod/` | ❌ | 老牌稳定 |
| ⭐ 速播资源 | `https://subocj.com/api.php/provide/vod/at/json` | ✅ | 支持搜索 |
| 魔爪资源 | `https://mozhuazy.com/api.php/provide/vod/at/xml` | ✅ | XML 格式 |
| 极速资源 | `https://jszyapi.com/api.php/provide/vod` | ✅ | 速度快 |
| 樱花资源 | `https://m3u8.apiyhzy.com/api.php/provide/vod/` | ❌ | 高清 |
| 闪电资源 | `http://sdzyapi.com/api.php/provide/vod/` | ❌ | 老牌 |
| 红牛资源 | `https://www.hongniuzy2.com/api.php/provide/vod/` | ❌ | 内容丰富 |
| 旺旺资源 | `https://api.wwzy.tv/api.php/provide/vod/at/xml/?ac=list` | ✅ | 支持搜索 |
| 猫眼资源 | `https://api.maoyanapi.top/api.php/provide/vod/at/xml` | ✅ | 支持搜索 |
| 百度资源 | `https://api.apibdzy.com/api.php/provide/vod/?ac=list` | ✅ | 百度资源 |
| 暴风资源 | `https://bfzyapi.com/api.php/provide/vod/at/xml` | ✅ | 支持搜索 |
| 光速资源 | `https://api.guangsuapi.com/api.php/provide/vod/at/xml/` | ✅ | 支持搜索 |
| 牛牛资源 | `https://api.niuniuzy.me/api.php/provide/vod/from/nnm3u8/at/xml` | ✅ | 支持搜索 |
| 细胞资源 | `https://www.xxibaozyw.com/api.php/provide/vod/at/xml/` | ✅ | 支持搜索 |
| 电影天堂 | `http://caiji.dyttzyapi.com/api.php/provide/vod/at/xml/` | ✅ | 经典资源 |
| 虎牙资源 | `https://www.huyaapi.com/api.php/provide/vod/at/json` | ✅ | 支持搜索 |
| 淘片资源 | `https://taopianapi.com/cjapi/sda/vod/json.html` | ✅ | 支持搜索 |
| 金鹰云资源 | `https://jyzyapi.com/provide/vod/from/jinyingyun/at/json` | ✅ | 支持搜索 |
| 豆瓣资源 | `https://caiji.dbzy5.com/api.php/provide/vod/at/josn/` | ✅ | 支持搜索 |
| 茅台资源 | `https://caiji.maotaizy.cc/api.php/provide/vod/at/josn/` | ✅ | 支持搜索 |
| 幸资源站 | `https://xzybb1.com/api.php/provide/vod/at/xml` | ✅ | 支持搜索 |
| CK伦理资源 | `https://ckzy.me/api.php/provide/vod/at/xml/?ac=list` | ✅ | 支持搜索 |
| ikun资源 | `https://ikunzyapi.com/api.php/provide/vod/from/ikm3u8/at/json` | ✅ | 支持搜索 |
| 金鹰资源 | `https://jyzyapi.com/provide/vod/at/xml/` | ✅ | 支持搜索 |

---

## 三、直播源 / IPTV（live）

> IPTV 直播源，支持电视直播观看。

### 3.1 推荐直播源

| 名称 | 链接 | 说明 |
|------|------|------|
| ⭐ chao921125/iptv | [raw](https://raw.githubusercontent.com/chao921125/source/main/iptv/index.m3u) | 含 EPG，推荐 |
| github iptv-org | [raw](https://raw.githubusercontent.com/iptv-org/iptv/master/streams/cn.m3u) | 官方 IPTV 组织 |
| 天光云影 | [raw](https://raw.githubusercontent.com/YueChan/Live/main/IPTV.m3u) | 国内直播源 |

### 3.2 EPG 节目单

| 名称 | 链接 |
|------|------|
| EPG 112114 | `https://epg.112114.eu.org/?ch={name}&date={date}` |
| EPG Logo | `https://epg.112114.eu.org/logo/{name}.png` |

---

## 四、云盘源 / Alist（cloud）

> 网盘资源，支持 Alist、天翼云盘等。
> Zyfun 支持 Alist 适配器，可直接挂载网盘资源。

| 名称 | 地址 | 类型 |
|------|------|------|
| 🙋 丫仙女 | `http://alist.xiaoya.pro/` | Alist |
| 🤮 布满灰尘 | `https://pan.baiblog.ren/` | Alist |
| 🌊 七米蓝 | `https://al.chirmyram.com` | Alist |
| 🐉 神族九帝 | `https://alist.shenzjd.com` | Alist |
| ☃ 姬路白雪 | `https://pan.jlbx.xyz` | Alist |
| 🎧 星梦 | `https://pan.bashroot.top` | Alist |

> ⚠️ 部分云盘源可能已失效，请以实际测试为准。

---

## 五、drpy 源（drpy）

> drpy 格式的 JS 资源源，需配合 drpy 使用。

| 名称 | 链接 | 说明 |
|------|------|------|
| chao921125/drpy_dz | [GitHub](https://github.com/chao921125/source/tree/main/zyfun/drpy_dz) | drpy 定制源 |
| chao921125/drpy_dzlive | [GitHub](https://github.com/chao921125/source/tree/main/zyfun/drpy_dzlive) | drpy 直播源 |
| chao921125/drpy_gao | [GitHub](https://github.com/chao921125/source/tree/main/zyfun/drpy_gao) | drpy 高赞源 |

---

## 六、TVBox 兼容源（tvbox）

> 这些是 TVBox 格式的完整配置文件，Zyfun 也可以导入其中的部分数据。

### 6.1 GitHub 仓库源

| 仓库 | 说明 | Stars |
|------|------|-------|
| [chao921125/source](https://github.com/chao921125/source) | 最全面，含 Zyfun + TVBox + IPTV | ⭐ |
| [noimank/tvbox](https://github.com/noimank/tvbox) | TVBox 多仓合集 | 2.7k |
| [qist/tvbox](https://github.com/qist/tvbox) | OK影视/TVBox/猫影视配置 | 5.7k |
| [ngo5/IPTV](https://github.com/ngo5/IPTV) | TVBOX 直播点播源收集 | - |
| [Zhou-Li-Bin/Tvbox-QingNing](https://github.com/Zhou-Li-Bin/Tvbox-QingNing) | 永久免费更新 | - |

### 6.2 在线订阅链接（TVBox 格式）

| 名称 | 链接 |
|------|------|
| 巧技 | `http://cdn.qiaoji8.com/tvbox.json` |
| 王小二 | `http://tvbox.xn--4kq62z5rby2qupq9ub.top/` |
| 讴歌 | `http://tv.nxog.top/m` |
| 饭太硬 | `http://www.饭太硬.top/tv/` |
| 摸鱼儿 | `http://我不是.摸鱼儿.com` |
| 肥猫 | `http://我不是.肥猫.live/` |
| 南风 | `https://ghproxy.net/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json` |
| 天微 | `https://qixing.myhkw.com/tianwei/svip.json` |
| 天微4K | `https://tvkj.top/tv4k/svip.json` |
| 七星 | `https://tvkj.top/QX/svip.json` |
| 小米 | `http://xhww.fun:63/小米/DEMO.json` |
| OK杰克 | `http://ok321.top/ok` |
| 菜妮丝 | `https://tvbox.cainisi.cf` |
| 月光宝盒 | `https://jihulab.com/ygbh1/box/-/raw/main/月光宝盒` |
| 神器 | `https://神器每日推送.tk/pz.json` |
| 那里花开 | `http://hz752.love:63/tk.json` |
| 吾爱有三 | `http://52bsj.vip:98/0805` |
| 潇洒 | `https://download.kstore.space/download/2863/01.txt` |
| 运输车 | `https://github.moeyy.xyz/https://raw.githubusercontent.com/52670576/tvbox/main/ysc.json` |
| FongMi | `https://999740.xyz/https://raw.githubusercontent.com/gaotianliuyun/fongmi/main/json/config.json` |
| 心魔 | `https://jihulab.com/yw88075/tvbox/-/raw/main/dr/js.json` |

---

## 七、一站式源合集

> 以下是包含多种类型源的完整配置文件，一键导入即可使用。

### Zyfun 格式（推荐）

```json
{
  "name": "chao921125/source（最全面）",
  "url": "https://raw.githubusercontent.com/chao921125/source/main/zyfun/index.json",
  "description": "30+ 解析接口 + 28+ CMS + 直播源 + 云盘源",
  "subscribe_url": "https://raw.githubusercontent.com/chao921125/source/main/zyfun/index.json"
}
```

### TVBox 格式

| 名称 | 链接 | 说明 |
|------|------|------|
| 综合推荐 | `http://cdn.qiaoji8.com/tvbox.json` | 巧技，综合 |
| 南风 | `https://ghproxy.net/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json` | 稳定 |
| 天微4K | `https://tvkj.top/tv4k/svip.json` | 4K 源 |

---

## 🔗 推荐订阅链接汇总

### Zyfun 格式（推荐）

```
# 最全面（30+ 解析 + 28+ CMS + 直播 + 云盘）
https://raw.githubusercontent.com/chao921125/source/main/zyfun/index.json
```

### TVBox 格式

```
# 综合推荐
http://cdn.qiaoji8.com/tvbox.json

# 南风（稳定）
https://ghproxy.net/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json

# 天微（4K）
https://tvkj.top/tv4k/svip.json
```

---

## 📦 Zyfun 客户端下载

| 平台 | 下载 |
|------|------|
| Windows | [Releases](https://github.com/Hiram-Wong/zyfun/releases/latest/download/zyfun-win-3.4.6-x64-setup.exe) |
| macOS | [Releases](https://github.com/Hiram-Wong/zyfun/releases/latest/download/zyfun-mac-3.4.6-arm64.dmg) |
| Linux (deb) | [Releases](https://github.com/Hiram-Wong/zyfun/releases/latest/download/zyfun-linux-3.4.6-amd64.deb) |
| Linux (AppImage) | [Releases](https://github.com/Hiram-Wong/zyfun/releases/latest/download/zyfun-linux-3.4.6-x86_64.AppImage) |

---

## ⚠️ 注意事项

1. **不要开启 VPN/代理**，可能导致 IP 变动使源失效
2. 导入后如果软件打不开，说明接口有脏数据，需删除数据库文件重启
3. 部分源可能随时失效，建议收藏本仓库获取最新更新
4. Zyfun 需 3.3.4+ 版本才能导入大部分源
5. 配置后记得 **刷新** 或 **重启软件**

---

## 📝 更新记录

- **2026-06-06**: 新增独立解析接口列表、TVBox 兼容源、云盘源分类
- **2026-06-05**: 初始版本，全面整理自 GitHub 社区

---

## ⚖️ 免责声明

本项目仅收集和整理互联网上公开分享的视频源配置，仅供学习交流使用。
所有资源均来自第三方，本项目不提供任何视频内容服务。
请勿用于商业用途。如有侵犯权益，请联系删除。
