![TRUEODS — 水晶双环主视觉](media/brand/trueods-v24.png)

# TRUEODS
### 面向 Unreal Engine 的 360° 立体全景渲染。

[English](README.md) · **简体中文**

我们为高分辨率 **360° ODS 与 VR180 ODS** 制作开发渲染工具，提供 Lumen 下正确立体视差、分钟级 8K 双眼渲染、无缝体积渲染和线性 HDR 母版。

支持的体积类型包括**高度雾与体积雾、网格体积材质、Local Fog Volume（局部雾体积）、Volumetric Cloud（体积云），以及 VDB / Heterogeneous Volumes（异质体积）**。Niagara 的 sprite 和拖尾（ribbon）使用默认设置即可无缝渲染，CPU 或 GPU 模拟均适用，不需要额外配置。也支持用于蒸汽、雨、浮尘和烟的粒子贴片，以及自定义雾效果。

<sub>已公布的性能数据使用插件 Version 67（v12）实测。</sub>

[了解 TRUEODS](https://github.com/trueodsofficial/trueods/blob/main/README.zh-CN.md) · [样片下载](https://github.com/trueodsofficial/trueods/blob/main/README.zh-CN.md#样片下载) · [快速上手](https://github.com/trueodsofficial/trueods/blob/main/docs/QUICKSTART.zh-CN.md) · [获得支持](https://github.com/trueodsofficial/trueods/blob/main/docs/SUPPORT.zh-CN.md)

## 从一台工作站，到团队协作

| TrueODS 基础版 | TrueODS Distributed（分布式渲染版） |
| :--- | :--- |
| 完整的立体全景渲染能力，适合独立创作者与单机制作。 | 包含基础版全部能力，增加团队制作所需的**引擎级时序锁定**与**多机协同渲染**。 |

**分布式渲染版让分开渲染的片段保持场景时间连贯**。多机协同渲染自动校验配置、分配帧段、检查收帧完整性；工程部署以及每台机器的启动与续渲由你完成。未烘焙的模拟、随机或外部驱动的效果，以及需要多帧才能稳定的光照与效果，仍需缓存、预热与接点检查。

[查看版本比较 →](https://github.com/trueodsofficial/trueods/blob/main/docs/EDITIONS.zh-CN.md)

[TrueODS 基础版操作教程（中文）](https://www.bilibili.com/video/BV1MSpz6QEHJ/) · [多机渲染操作教程（中文）](https://www.bilibili.com/video/BV1yjpz65Eqy/)

## 每个方向都有正确立体视差

![内景 — 左右眼交替展示立体视差](media/showcase/interior-stereo.webp)

[JPG · 26.5 MB](https://github.com/trueodsofficial/trueods/releases/download/samples-20260928/coffee01_00108409.jpg) · [PNG 原图 · 295.8 MB](https://github.com/trueodsofficial/trueods/releases/download/samples-20260928/coffee01_00108409.png)

<sub>上下两极的重影来自 Pole Mono Merge（单眼融合），并非渲染瑕疵。</sub>

左右眼交替的全景预览。[查看更多画面与输出说明 →](https://github.com/trueodsofficial/trueods/blob/main/README.zh-CN.md#看实际效果)

<sub>环境资产：**Leartes Studios** 的 [Coffee Shop Environment](https://www.fab.com/listings/a0c7819e-a61d-4a19-8d3b-f0f5e584e6e0)。</sub>

## 联系与文档

- **产品文档**：[TRUEODS 使用指南](https://github.com/trueodsofficial/trueods/blob/main/README.zh-CN.md)
- **购买前咨询**：[售前咨询与效果交流（Telegram）](https://t.me/+jWlt-pgGHtRlOGUx) · [WhatsApp 售前群](https://chat.whatsapp.com/KEIad2ctdbb1oQp1wuYheH?mode=gi_t)
- **支持邮箱**：[trueodssupport@gmail.com](mailto:trueodssupport@gmail.com)
- **售后群**：[申请加入 Telegram 售后群](https://github.com/trueodsofficial/trueods/blob/main/docs/COMMUNITY.zh-CN.md)；邮件发送订单凭证，回复获取邀请链接。
- **Fab 购买入口**：[TrueODS 基础版](https://www.fab.com/listings/ad60562e-7897-46f6-995b-6e75639972fb) — **Personal：US$399.99** · [TrueODS Distributed（分布式渲染版）](https://www.fab.com/listings/c6178ce6-987a-4b29-9f55-033ed30df4bf) — **Personal：US$1,499.99**。
