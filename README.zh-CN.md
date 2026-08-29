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

把人物设定、服装、鞋袜、包袋、配饰与情绪描述，整理成统一的时尚人物设定板：

- Front 正面
- Side 90°侧面
- Back 背面
- Headshot 情绪近景

默认采用白色极简摄影棚、柔和高调光线、真实皮肤与服装材质，以及 Fashion Lookbook / Character Sheet 排版。

**适合：** 人物三视图、穿搭图鉴、角色设定板、表情图鉴、多套服装批量提示词。

➡️ **[打开 Skill 01](./skills/01-three-view-emotion-outfit-board/SKILL.md)**

---

### 02｜镜面自拍穿搭情绪 Look Book 生成器
**Mirror Selfie Lookbook Emotion Board**

把室内全身镜自拍、多套都市穿搭和对应微表情，整理成统一的黑色杂志式 Look Book：

- Front 正面镜自拍
- Side 侧面镜自拍
- Back 背面镜自拍
- Headshot 完整面部情绪大头贴

固定低饱和黑灰室内环境、真实手机摄影、自然身体比例，并严格保持同一成年人物、同一发型、同一服装、同一鞋子、同一手机与同一场景。

### 内置 8 套 Look

1. 黑色吊带迷你裙｜委屈感
2. 白衬衫＋黑色皮裙｜无辜眼神
3. 黑色露肩娃娃裙｜期待
4. 白衬衫＋白色包臀长裙｜放松呼吸感
5. 灰蓝吊带＋白色迷你裙｜小得意
6. 咖啡色修身连体短裤｜慢半拍微笑
7. 裸粉上衣＋白色迷你裙｜欲言又止
8. 裸粉色 A 字短裙｜偷看镜头

**适合：** 都市穿搭 Look Book、镜面自拍参考板、角色衣橱设定、服装档案、情绪大头贴。

➡️ **[打开 Skill 02](./skills/02-mirror-selfie-lookbook-emotion-board/SKILL.md)**

---

## 仓库结构

```text
.
├── README.md                       # 语言入口 / Language selector
├── README.zh-CN.md                # 中文说明
├── README.en.md                   # English documentation
├── SKILL.md                       # 原始兼容入口
└── skills/
    ├── 01-three-view-emotion-outfit-board/
    │   └── SKILL.md
    └── 02-mirror-selfie-lookbook-emotion-board/
        └── SKILL.md
```

后续新增 Skill 继续按编号排列：

```text
03-skill-name/
04-skill-name/
05-skill-name/
```

---

## 使用方法

打开需要的 `SKILL.md`，把完整规则导入支持 Skill / Agent 指令的工作流即可。

每个 Skill 会尽量包含：

- 功能说明
- 触发意图
- 执行逻辑
- 人物与服装一致性规则
- 输出模板
- 安全边界

---

## 语言切换

<p align="center">
  <a href="./README.zh-CN.md"><kbd>🇨🇳 中文说明</kbd></a>
  &nbsp;&nbsp;
  <a href="./README.en.md"><kbd>🇺🇸 English</kbd></a>
</p>
