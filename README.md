# 世界酒类百科内容源

`world-alcohol-encyclopedia` 是喝酒去唯一的内容源仓。四个内容域放在同一仓内，站点只读取对应的子目录；共享媒体也放在这里。

| 目录 | 内容 | 站点 |
| --- | --- | --- |
| `beverages/` | 酒类、风格、品牌、生产者、产区、鸡尾酒等识酒内容 | `beverages.hejiu.org` |
| `guide/` | 喝法、品鉴、侍饮、配方、器具与配餐 | `hejiu.org` |
| `culture/` | 历史、人物、典籍、礼俗、艺术与诗词 | `culture.hejiu.org` |
| `atlas/` | 酒馆、酒庄、博物馆、活动与路线 | `atlas.hejiu.org` |
| `media/` | 四个站点共享的图片与媒体文件 | 各站 `/media/...` |

每个内容域仍保持 `{lang}/{type}/{slug}.md` 的路径和独立 README / 语言目录索引。内容身份、关系、来源、权利与翻译状态由 `site-alcohol-core` 的构建器统一校验。

内容许可见 `LICENSE-CONTENT.md`；代码许可见根 `LICENSE`。第三方图片、商标与引用文本不在项目许可内。
