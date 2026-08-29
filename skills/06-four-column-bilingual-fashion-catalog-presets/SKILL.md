---
name: four-column-bilingual-fashion-catalog-presets
description: Generate clean bilingual fashion catalog posters with a consistent adult model, Front/Side/Back/Headshot four-column layout, bilingual outfit titles, bilingual expression subtitles, and eight built-in outfit presets. 生成统一成年模特的极简双语时装图鉴海报，固定 Front/Side/Back/Headshot 四栏排版、中英标题与表情副标题，并内置 8 套穿搭预设。
version: 1.0.0
language:
  - zh-CN
  - en
---

# 06 — Four-Column Bilingual Fashion Catalog Presets
# 06 — 四栏中英双语时装图鉴预设

[中文](#中文) | [English](#english)

---

## 中文

### 1. Skill 功能

这个 Skill 用于把**同一位明确成年的年轻亚洲女性、固定服装、对应表情、中英文标题与四栏服装展示结构**整理成可直接用于图像生成模型的时尚 Lookbook / Catalog 提示词。

默认视觉：

- 浅米白纯色背景
- 柔和均匀影棚光
- 高级、干净、统一的商品详情页 / 时装画册风格
- 同一人物身份、发型、肤色、身材比例始终保持一致
- 四栏排版：Front / Side / Back / Headshot
- 顶部中英双语穿搭标题
- 标题下方中英双语表情副标题
- 底部四栏中英双语标签

### 2. 默认人物设定

除非用户另行指定，默认人物为：

> 同一位明确成年的年轻亚洲女性，长款深棕偏黑色微卷发，白皙自然肤色，五官清秀柔和，身材纤细高挑，真实皮肤纹理，清透自然妆容。

如果用户提供人物参考图，则参考图优先，必须保持：

- 脸型
- 五官
- 发型与发色
- 肤色
- 年龄感
- 身材比例
- 整体辨识度

### 3. 固定画面结构

整张海报固定为 **4 栏**：

1. 正面 Front
2. 侧面 Side
3. 背面 Back
4. 大头贴 Headshot

前三栏必须展示完整服装全身视图，人物站姿自然，不夸张扭腰扭胯。

第四栏为近距离 Headshot，完整展示指定微表情，并尽量保留领口、肩部或上装关键细节以维持服装一致性。

### 4. 固定文字结构

顶部标题：

`OUTFIT X · 中文名 / English Name`

标题下方副标题：

`表情 / EXPRESSION：中文表情 / English Expression`

底部标签：

- 正面 Front
- 侧面 Side
- 背面 Back
- 大头贴 Headshot

文字风格：

- 简洁无衬线字体
- 黑色或深灰文字
- 清晰可读
- 不遮挡人物
- 不出现乱码
- 不随意改写用户指定的中英文名称

### 5. 视觉质量规则

默认强化：

- realistic skin texture
- realistic fabric texture
- soft studio lighting
- clean cream-beige background
- premium fashion catalog
- product-detail-page aesthetic
- consistent character identity
- consistent outfit construction
- natural body proportions
- clean typography
- balanced four-column spacing

避免：

- 人物身份漂移
- 三视图服装变化
- 鞋子、包袋、首饰消失或变形
- 发型前后不一致
- 截断脚部
- 多余手指
- 四肢重复
- 过度磨皮
- 背景杂乱
- 标题乱码
- 标签错位

### 6. 执行逻辑

#### Step 1 — 锁定人物

提取人物参考与基础设定，并保持所有视图为同一人物。

#### Step 2 — 提取每套服装

识别：

- 中文服装名
- English Name
- 上装 / 连衣裙
- 下装
- 材质
- 颜色
- 鞋子
- 包袋
- 首饰或装饰

#### Step 3 — 提取表情

将中文表情名与英文表情名一一对应，并转成明确可视觉化的：

- 头部角度
- 眼神方向
- 眉毛状态
- 嘴角 / 嘴唇动作
- 手部辅助动作

#### Step 4 — 建立四栏一致性

Front / Side / Back 必须完全同一套服装。Headshot 也必须保持相同人物、发型、妆容和对应上装细节。

#### Step 5 — 输出

用户提供多套穿搭时，每套独立输出完整提示词，不把不同 LOOK 混在一起。

---

## 7. 内置 8 套 OUTFIT 预设

### OUTFIT 1｜棕色抹胸 + 毛绒披肩套装 / Brown Bandeau and Faux-Fur Shawl Set

服装：咖啡棕色抹胸短上衣，外搭浅棕色毛绒披肩 / 毛绒短外套；同色系低腰修身超短裤，腰部带围裹式垂坠绑带设计；棕色尖头低跟鞋。

表情：坏笑得意 / Smug Mischievous Smirk。头略微低下，一侧眼睛轻眯，嘴角轻轻歪起，带一点暗爽、挑衅和得意。

### OUTFIT 2｜奶油白荷叶边两件套 / Cream White Ruffled Two-Piece Set

服装：无袖高领荷叶边短上衣，层叠木耳边与褶皱设计，领口点缀红色蝴蝶结；同材质层叠荷叶边超短裙，腰部带红色蝴蝶结；奶油白玛丽珍鞋。

表情：仰头发呆 / Upward Blank Stare。头向后仰并偏向一侧，眼睛看向上方，嘴唇微张，带一点走神和疑惑感。

### OUTFIT 3｜奶油白细肩带修身短裙 / Cream White Spaghetti-Strap Bodycon Mini Dress

服装：奶油白细肩带包臀迷你连衣裙，胸前立体蝴蝶 / 花朵装饰，肩带带金属链感细节，腰臀自然褶皱；浅金或米白色细带高跟凉鞋；棕色单肩包。

表情：捧脸无辜 / Innocent Face-Cupping。双手轻贴两侧脸颊，头略偏，眼神向侧上方看，嘴角放松，呆萌无辜。

### OUTFIT 4｜裸咖色不对称修身短裙 / Nude Taupe Asymmetric Bodycon Mini Dress

服装：裸咖色细肩带修身迷你连衣裙，胸前大面积蕾丝刺绣，腰臀褶皱明显，一侧垂坠不对称薄纱裙片；裸色细带高跟鞋；棕色单肩包。

表情：嫌弃憋屈 / Annoyed and Aggrieved。双手托住脸颊，鼻子微皱，眉眼挤压，嘴角向下，像在强忍不爽。

### OUTFIT 5｜黑色挂脖修身短裙 / Black Halter Bodycon Mini Dress

服装：黑色挂脖无袖迷你连衣裙，高领绕颈设计，领口大面积银色水钻与珠饰，胸前小面积镂空，修身包臀剪裁，裙摆轻微毛边；黑色细带高跟凉鞋；棕色单肩包。

表情：侧目偷看 / Side Glance Peek。头微微侧转，眼睛斜向一侧看，嘴唇轻抿，带一点警惕和小心思。

### OUTFIT 6｜姜黄色长袖超短连衣裙 / Mustard Yellow Long-Sleeve Mini Dress

服装：姜黄色修身长袖迷你连衣裙，翻领、深 V 领口，内搭黑色小背心，腰部明显收紧，裙摆轻微外扩并带细褶；黑色细带高跟凉鞋。

表情：咬指思考 / Finger-to-Lip Thinking Pose。头微微倾斜，手指轻触嘴唇，眼神平静看向镜头，若有所思。

### OUTFIT 7｜紫色斜肩挂脖包臀裙 / Purple One-Shoulder Halter Bodycon Dress

服装：深紫色修身迷你连衣裙，单肩斜挂脖设计，一侧肩部延伸轻薄飘带，胸腰臀位置自然抽褶，紧身包臀版型；黑色细带高跟凉鞋。

表情：托腮撒娇 / Cheek-Resting Cutesy Pose。一只手贴住脸颊，脸轻轻压向手掌，嘴唇微嘟，眼神柔软又略带一点委屈。

### OUTFIT 8｜黑色抹胸连体短裤 / Black Strapless Romper

服装：黑色抹胸连体短裤，上身无肩带修身设计，胸前夸张银色蝴蝶结 / 水钻项链装饰，腰部收紧，下装高腰短裤；黑色细带高跟凉鞋；棕色单肩包。

表情：冷静直视 / Calm Direct Gaze。正面对镜头，头部端正，双眼平静直视，嘴唇自然闭合，神情淡漠克制。

---

## 8. 默认输出模板

```text
同一位明确成年的年轻亚洲女性，长款深棕偏黑色微卷发，白皙自然肤色，五官清秀柔和，身材纤细高挑。浅米白纯色背景，柔和均匀影棚光，真实皮肤与服装纹理，高级极简 Fashion Lookbook / Catalog / Character Sheet 风格。

画面采用四栏排版：正面 Front / 侧面 Side / 背面 Back / 大头贴 Headshot。前三栏展示完整全身服装视图，第四栏展示对应微表情近景。四栏保持完全同一人物、同一发型、同一妆容、同一服装、同一鞋履与配饰。

顶部标题：OUTFIT X · 【中文服装名】 / 【English Name】
副标题：表情 / EXPRESSION：【中文表情】 / 【English Expression】
底部标签：正面 Front / 侧面 Side / 背面 Back / 大头贴 Headshot

服装：【完整服装描述】
表情：【完整表情动作描述】

整体排版整洁、文字清晰、留白均衡，像高级时装画册、服装商品详情页与人物设定板。
```

### 9. 可选模式

用户需要时可输出：

- 中文完整版
- English Prompt
- ChatGPT-Image 版
- Midjourney 版
- Flux / SDXL 版
- 精简省 Token 版
- 批量 8 套完整版
- JSON 变量版

### 10. 安全边界

- 人物必须明确为成年人
- 默认保持时装展示、服装图鉴和正常人物写真范围
- 不生成露骨色情内容
- 不生成违法、仇恨或图形化暴力内容
- 遇到年龄歧义时，自动明确为成年人物

---

## English

### 1. Purpose

This Skill generates clean premium bilingual fashion-catalog posters using one consistent clearly adult Asian female model.

Default visual system:

- light cream-beige seamless background
- soft even studio lighting
- premium minimal catalog aesthetic
- four columns: Front / Side / Back / Headshot
- bilingual outfit title at the top
- bilingual expression subtitle below the title
- bilingual labels under each column

### 2. Default Model

Unless overridden by the user:

> The same clearly adult young Asian woman, long dark-brown to black softly wavy hair, fair natural skin, soft refined facial features, slim tall proportions, natural makeup, and realistic skin texture.

If a reference image is supplied, preserve identity, facial structure, hairstyle, skin tone, age impression, body proportions, and overall recognizability.

### 3. Fixed Layout

The poster always contains four columns:

1. Front
2. Side
3. Back
4. Headshot

The first three columns show complete full-body outfit views. The final column is a close-up facial portrait with the specified expression while preserving the same character, hairstyle, makeup, and visible outfit details.

### 4. Typography

Top title:

`OUTFIT X · Chinese Name / English Name`

Subtitle:

`表情 / EXPRESSION: Chinese Expression / English Expression`

Bottom labels:

- 正面 Front
- 侧面 Side
- 背面 Back
- 大头贴 Headshot

Use clean sans-serif typography, high legibility, balanced spacing, and no garbled text.

### 5. Consistency Rules

Preserve the same:

- model identity
- hairstyle
- makeup
- body proportions
- outfit construction
- shoes
- bags
- jewelry
- fabric color and texture

Avoid duplicated limbs, cropped feet, malformed hands, inconsistent garments, disappearing accessories, distorted typography, or cluttered backgrounds.

### 6. Built-in Presets

1. Brown Bandeau and Faux-Fur Shawl Set — Smug Mischievous Smirk
2. Cream White Ruffled Two-Piece Set — Upward Blank Stare
3. Cream White Spaghetti-Strap Bodycon Mini Dress — Innocent Face-Cupping
4. Nude Taupe Asymmetric Bodycon Mini Dress — Annoyed and Aggrieved
5. Black Halter Bodycon Mini Dress — Side Glance Peek
6. Mustard Yellow Long-Sleeve Mini Dress — Finger-to-Lip Thinking Pose
7. Purple One-Shoulder Halter Bodycon Dress — Cheek-Resting Cutesy Pose
8. Black Strapless Romper — Calm Direct Gaze

### 7. Output Template

```text
The same clearly adult young Asian woman with long dark-brown to black softly wavy hair, fair natural skin, soft refined facial features, and slim tall proportions. Light cream-beige seamless studio background, soft even studio lighting, realistic skin and fabric texture, premium minimal Fashion Lookbook / Catalog / Character Sheet aesthetic.

Use a four-column layout: Front / Side / Back / Headshot. The first three columns show complete full-body outfit views. The fourth column shows the matching facial expression. Keep the exact same identity, hairstyle, makeup, outfit, shoes, bag, and accessories across all four columns.

Top title: OUTFIT X · [Chinese Outfit Name] / [English Outfit Name]
Subtitle: 表情 / EXPRESSION: [Chinese Expression] / [English Expression]
Bottom labels: 正面 Front / 侧面 Side / 背面 Back / 大头贴 Headshot

Outfit: [full outfit description]
Expression: [full expression description]

Clean spacing, legible bilingual typography, premium fashion-catalog presentation, refined natural photography.
```

### 8. Safety

The model must be clearly adult. Keep the output within normal fashion-catalog, character-design, and portrait-photography contexts. Do not generate explicit sexual content, illegal content, hateful content, or graphic violence.
