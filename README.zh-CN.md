# You Know What I Mean — Skill 合集

<p align="center">
  <a href="./README.zh-CN.md"><kbd>🇨🇳 中文说明</kbd></a>
  &nbsp;&nbsp;
  <a href="./README.en.md"><kbd>🇺🇸 English</kbd></a>
  &nbsp;&nbsp;
  <a href="./docs/SKILL-USAGE.zh-CN.md"><kbd>📘 Skill 使用教程</kbd></a>
  &nbsp;&nbsp;
  <a href="./docs/RIGHTS-SAFETY.zh-CN.md"><kbd>⚠️ 版权 / 肖像权提醒</kbd></a>
</p>

> 一个持续整理的图像生成、人物设定与视觉工作流 Skill 仓库。

> **重要提醒：** 使用人物参考图、第三方照片、专辑封面、Logo、品牌 UI、字体或其他素材，并不代表你自动拥有相关版权、肖像权或商业使用权。公开发布或商业使用前，请确认授权、隐私、平台规则与适用法律。完整说明：**[版权、肖像权与人物参考图使用提醒](./docs/RIGHTS-SAFETY.zh-CN.md)**。

---

## 新手先看

第一次使用建议先打开：

➡️ **[Skill 使用说明教程](./docs/SKILL-USAGE.zh-CN.md)**

同时建议阅读：

➡️ **[版权、肖像权与人物参考图使用提醒](./docs/RIGHTS-SAFETY.zh-CN.md)**

尤其当你要使用真人参考图、明星 / 网红形象、专辑封面、品牌 Logo、真实 UI，或者准备商用时。

教程包含：

- Skill 是什么
- 怎么选择对应 Skill
- 怎么导入 `SKILL.md`
- 怎么使用人物参考图
- 怎么替换 `{{变量}}`
- 怎么调用内置 OUTFIT / LOOK
- 怎么一次批量生成多套
- ChatGPT-Image / Midjourney / Flux / SDXL 怎么适配
- 人物漂移、服装漂移、手部错误、文字乱码怎么处理
- 怎么继续新增自己的预设

---

## Skill 索引

### 01｜三视图情绪穿搭图鉴生成器
**Three-View Emotion Outfit Board Generator**

把人物设定、服装、鞋袜、包袋、配饰与情绪描述整理成 Front / Side / Back / Headshot 时尚人物设定板。

➡️ **[打开 Skill 01](./skills/01-three-view-emotion-outfit-board/SKILL.md)**

### 02｜镜面自拍穿搭情绪 Look Book 生成器
**Mirror Selfie Lookbook Emotion Board**

黑灰室内镜面自拍 Look Book，固定同一人物、同一环境、同一服装与对应情绪大头贴。

➡️ **[打开 Skill 02](./skills/02-mirror-selfie-lookbook-emotion-board/SKILL.md)**

### 03｜白色摄影棚穿搭情绪预设图鉴
**White Studio Outfit Emotion Presets**

内置 8 套白色摄影棚穿搭和情绪预设，统一生成 Front / Side / Back / Headshot。

➡️ **[打开 Skill 03](./skills/03-white-studio-outfit-emotion-presets/SKILL.md)**

### 04｜暗黑电影情绪角色设定卡预设
**Dark Emotion Character Card Presets**

暗黑电影角色档案：大尺寸情绪特写 + Front / 3/4 View / Side + 手绘 Headshot + PROP 标签。

➡️ **[打开 Skill 04](./skills/04-dark-emotion-character-card-presets/SKILL.md)**

### 05｜超广角 UI × 真人街头广告视觉预设
**Ultrawide UI Street Ad Presets**

24–28mm 强制透视、真人街拍与实体化手机 UI / 音乐卡片 / 地图 / 分享界面融合。

➡️ **[打开 Skill 05](./skills/05-ultrawide-ui-street-ad-presets/SKILL.md)**

### 06｜四栏中英双语时装图鉴预设
**Four-Column Bilingual Fashion Catalog Presets**

浅米白影棚，固定 Front / Side / Back / Headshot 四栏，中英双语服装标题、表情副标题和底部标签，内置 8 套 OUTFIT。

➡️ **[打开 Skill 06](./skills/06-four-column-bilingual-fashion-catalog-presets/SKILL.md)**

### 07｜中英双语婚纱四宫格图鉴预设
**Bilingual Wedding Lookbook Presets**

纯白影棚婚纱 Lookbook，固定 Front / Side / Back / Headshot 四宫格，中英婚纱标题与表情标签，内置 8 套婚纱。

➡️ **[打开 Skill 07](./skills/07-bilingual-wedding-lookbook-presets/SKILL.md)**

---

## 仓库结构

```text
.
├── README.md
├── README.zh-CN.md
├── README.en.md
├── SKILL.md
├── docs/
│   ├── SKILL-USAGE.zh-CN.md
│   ├── SKILL-USAGE.en.md
│   ├── RIGHTS-SAFETY.zh-CN.md
│   └── RIGHTS-SAFETY.en.md
└── skills/
    ├── 01-three-view-emotion-outfit-board/
    ├── 02-mirror-selfie-lookbook-emotion-board/
    ├── 03-white-studio-outfit-emotion-presets/
    ├── 04-dark-emotion-character-card-presets/
    ├── 05-ultrawide-ui-street-ad-presets/
    ├── 06-four-column-bilingual-fashion-catalog-presets/
    └── 07-bilingual-wedding-lookbook-presets/
```

后续继续按 `08 / 09 / 10...` 顺序新增。

---

## 最简单的使用方式

```text
1. 选择一个 Skill
2. 打开并导入对应 SKILL.md
3. 上传你有权使用的人物参考图（可选）
4. 告诉模型要使用哪个 LOOK / OUTFIT，或提供新的服装与表情
5. 指定输出 ChatGPT-Image / Midjourney / Flux / SDXL 版本
6. 每套 Look 独立输出
7. 公开发布或商用前再次确认人物与素材授权
```

完整操作请看：**[Skill 使用说明教程](./docs/SKILL-USAGE.zh-CN.md)**

风险说明请看：**[版权、肖像权与人物参考图使用提醒](./docs/RIGHTS-SAFETY.zh-CN.md)**

---

<p align="center">
  <a href="./README.en.md"><kbd>🇺🇸 English</kbd></a>
  &nbsp;&nbsp;
  <a href="./docs/SKILL-USAGE.zh-CN.md"><kbd>📘 Skill 使用教程</kbd></a>
  &nbsp;&nbsp;
  <a href="./docs/RIGHTS-SAFETY.zh-CN.md"><kbd>⚠️ 版权 / 肖像权提醒</kbd></a>
</p>
