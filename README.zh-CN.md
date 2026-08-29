# You Know What I Mean — Skill 合集

<p align="center">
  <a href="./README.zh-CN.md"><kbd>🇨🇳 中文说明</kbd></a>
  &nbsp;&nbsp;
  <a href="./README.en.md"><kbd>🇺🇸 English</kbd></a>
</p>

> 一个持续整理的图像生成、人物设定与视觉工作流 Skill 仓库。

---

## Skill 索引

### 01｜三视图情绪穿搭图鉴生成器
**Three-View Emotion Outfit Board Generator**

把人物设定、服装、鞋袜、包袋、配饰与情绪描述，整理成统一的时尚人物设定板：Front 正面 / Side 90°侧面 / Back 背面 / Headshot 情绪近景。

**适合：** 人物三视图、穿搭图鉴、角色设定板、表情图鉴、多套服装批量提示词。

➡️ **[打开 Skill 01](./skills/01-three-view-emotion-outfit-board/SKILL.md)**

---

### 02｜镜面自拍穿搭情绪 Look Book 生成器
**Mirror Selfie Lookbook Emotion Board**

把室内全身镜自拍、多套都市穿搭和对应微表情，整理成统一的黑色杂志式 Look Book，固定低饱和黑灰室内环境、真实手机摄影与自然身体比例。

**适合：** 都市穿搭 Look Book、镜面自拍参考板、角色衣橱设定、服装档案、情绪大头贴。

➡️ **[打开 Skill 02](./skills/02-mirror-selfie-lookbook-emotion-board/SKILL.md)**

---

### 03｜白色摄影棚穿搭情绪预设图鉴
**White Studio Outfit Emotion Presets**

固定预设版 Skill，内置 8 套白色摄影棚穿搭与对应情绪，统一生成 Front / Side / Back / Headshot 四类人物视图。

**适合：** 固定穿搭批量生图、角色服装档案、表情设定集、Fashion Lookbook、Character Sheet。

➡️ **[打开 Skill 03](./skills/03-white-studio-outfit-emotion-presets/SKILL.md)**

---

### 04｜暗黑电影情绪角色设定卡预设
**Dark Emotion Character Card Presets**

把强情绪表演、固定穿搭、荒诞小道具和电影感摄影整理成暗黑角色设定卡：左侧大尺寸情绪特写，右侧 Front / 3/4 View / Side，底部手绘 Headshot，并附中英文标题与 PROP 标签。

**适合：** 情绪角色档案、电影人物设定卡、暗黑时尚拼版、心理剧情概念海报、Character Sheet。

➡️ **[打开 Skill 04](./skills/04-dark-emotion-character-card-presets/SKILL.md)**

---

### 05｜超广角 UI × 真人街头广告视觉预设
**Ultrawide UI Street Ad Presets**

把人物参考图、街头时装、24–28mm 强制透视与实体化手机 UI 融合，生成超写实 3:4 竖版创意广告摄影。

**适合：** 创意街拍、音乐科技广告、手机 UI 视觉、潮流杂志大片、强制透视摄影、超现实商业广告。

➡️ **[打开 Skill 05](./skills/05-ultrawide-ui-street-ad-presets/SKILL.md)**

---

### 06｜四栏中英双语时装图鉴预设
**Four-Column Bilingual Fashion Catalog Presets**

固定浅米白影棚背景与四栏时装图鉴结构：正面 Front / 侧面 Side / 背面 Back / 大头贴 Headshot。顶部显示 `OUTFIT X · 中文名 / English Name`，标题下显示中英双语表情副标题，底部四栏继续使用中英双语标签。

### 内置 8 套 OUTFIT

1. 棕色抹胸 + 毛绒披肩套装｜坏笑得意
2. 奶油白荷叶边两件套｜仰头发呆
3. 奶油白细肩带修身短裙｜捧脸无辜
4. 裸咖色不对称修身短裙｜嫌弃憋屈
5. 黑色挂脖修身短裙｜侧目偷看
6. 姜黄色长袖超短连衣裙｜咬指思考
7. 紫色斜肩挂脖包臀裙｜托腮撒娇
8. 黑色抹胸连体短裤｜冷静直视

固定同一位明确成年的年轻亚洲女性，保持人物身份、发型、服装结构、鞋履、包袋与配饰在四栏中完全一致，并强化清晰双语排版、真实皮肤与服装材质。

**适合：** 时装 Lookbook、服装商品详情页、人物衣橱档案、四视图穿搭展示、双语 Fashion Catalog。

➡️ **[打开 Skill 06](./skills/06-four-column-bilingual-fashion-catalog-presets/SKILL.md)**

---

## 仓库结构

```text
.
├── README.md
├── README.zh-CN.md
├── README.en.md
├── SKILL.md
└── skills/
    ├── 01-three-view-emotion-outfit-board/
    │   └── SKILL.md
    ├── 02-mirror-selfie-lookbook-emotion-board/
    │   └── SKILL.md
    ├── 03-white-studio-outfit-emotion-presets/
    │   └── SKILL.md
    ├── 04-dark-emotion-character-card-presets/
    │   └── SKILL.md
    ├── 05-ultrawide-ui-street-ad-presets/
    │   └── SKILL.md
    └── 06-four-column-bilingual-fashion-catalog-presets/
        └── SKILL.md
```

后续继续按 `07 / 08 / 09...` 顺序新增。

---

## 使用方法

打开需要的 `SKILL.md`，把完整规则导入支持 Skill / Agent 指令的工作流即可。每个 Skill 会尽量包含功能说明、触发意图、执行逻辑、一致性规则、输出模板与安全边界。

---

## 语言切换

<p align="center">
  <a href="./README.zh-CN.md"><kbd>🇨🇳 中文说明</kbd></a>
  &nbsp;&nbsp;
  <a href="./README.en.md"><kbd>🇺🇸 English</kbd></a>
</p>
