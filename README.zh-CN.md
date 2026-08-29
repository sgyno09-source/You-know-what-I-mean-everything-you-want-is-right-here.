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

### 内置 7 套视觉模板

1. 悬浮音乐播放器卡片 + 极近镜头手势
2. 巨型照片分享 UI + 人物从屏幕里走出来
3. 三栏分享界面 + 坐姿人物突破照片边框
4. 胸前实体音乐播放器 + 白色有线耳机
5. 包袋内部第一人称视角 + 巨型来电 UI
6. 夸张大头小身体 + 巨手夹头错视
7. 第一人称脚下地图 UI 实体化

支持 `{{人物参考图}}`、`{{服装}}`、`{{歌曲名}}`、`{{专辑封面}}`、`{{城市}}`、`{{街道}}`、`{{目的地}}` 等变量替换，并强化正确手部结构、真实玻璃厚度、反射、阴影、遮挡和空间层级。

**适合：** 创意街拍、音乐科技广告、手机 UI 视觉、潮流杂志大片、强制透视摄影、超现实商业广告。

➡️ **[打开 Skill 05](./skills/05-ultrawide-ui-street-ad-presets/SKILL.md)**

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
    └── 05-ultrawide-ui-street-ad-presets/
        └── SKILL.md
```

后续继续按 `06 / 07 / 08...` 顺序新增。

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
