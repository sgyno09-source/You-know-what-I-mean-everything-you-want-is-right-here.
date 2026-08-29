---
name: three-view-nine-emotion-character-sheet
description: Generate a clean realistic character sheet using one consistent clearly adult female reference, with Front/Side/Back full-body views on top and nine distinct half-body emotion-action references below. 生成统一成年女性人物设定参考图，上半部分固定 Front/Side/Back 三视图，下半部分固定 9 组明显不同的半身情绪动作参考。
version: 1.0.0
language:
  - zh-CN
  - en
---

# 08 — Three-View + Nine-Emotion Character Sheet
# 08 — 三视图 + 九组情绪动作人物设定参考图

[中文](#中文) | [English](#english)

---

## 中文

### 1. Skill 功能

这个 Skill 用于把**同一位明确成年的女性人物参考图 + 指定穿搭**整理成一张干净统一的人物设定参考图 / Character Sheet。

固定画面结构：

- 上半部分：完整全身三视图
  - 正面 FRONT
  - 侧面 SIDE
  - 背面 BACK
- 下半部分：9 个半身情绪动作参考

核心目标：

- 人物身份高度统一
- 三视图服装结构前后一致
- 9 个表情动作明显不同
- 眼神方向有变化，不全部直视镜头
- 动作与情绪一一对应
- 不重复姿势
- 不出现多余人物
- 保持真人写实、韩系杂志模特参考图、时尚 Lookbook / Character Sheet 质感

---

### 2. 默认人物设定

如果用户提供人物参考图，必须以该参考图作为唯一身份来源，并优先保持：

- 五官
- 脸型
- 肤色
- 发型与发色
- 年龄感
- 整体气质
- 身材比例
- 整体辨识度

默认人物描述：

> 同一位明确成年的年轻亚洲女性，真人写实，五官清秀柔和，白皙自然肤色，身材纤细高挑，精致自然妆容，高级韩系时尚写真质感。

默认发型：

> 黑色头发盘成低位发髻，两侧自然碎发，白色花朵发饰，珍珠耳坠。

如果用户明确要求替换发型、首饰或妆容，可以替换；否则保持默认设定不变。

---

### 3. 默认摄影与背景

统一使用：

- 浅米白纯色摄影棚背景
- 柔和均匀棚拍布光
- 高清真实摄影质感
- 真实皮肤纹理
- 真实头发细节
- 真实服装材质
- 干净浅色背景
- 构图整齐
- 高级韩系杂志模特参考图
- 时尚 Lookbook
- 人物设定集 / Character Sheet

不要添加复杂场景、环境道具或无关装饰。

---

### 4. 固定上半部分：完整全身三视图

上半部分必须展示人物从头到脚的完整全身：

1. 正面 FRONT
2. 侧面 SIDE
3. 背面 BACK

三视图必须严格保持：

- 同一人物
- 同一张脸
- 同一发型
- 同一发饰
- 同一耳饰
- 同一套衣服
- 同一双鞋
- 同一身材比例
- 同一妆容
- 同一摄影棚
- 同一光线方向与风格

人物比例统一，站姿自然，不夸张扭腰扭胯。

正面、侧面、背面必须准确展示服装结构，包括：

- 领口
- 肩带 / 袖型
- 腰线
- 裙摆 / 裤型
- 面料
- 图案
- 蝴蝶结 / 拉链 / 纽扣
- 背部结构
- 鞋履
- 包袋与首饰（如果有）

禁止出现：

- 正面和背面变成不同衣服
- 裙长变化
- 鞋子变化
- 发型变化
- 饰品随机增加或消失
- 人物脸型漂移

---

### 5. 穿搭变量

穿搭位置固定为：

`【这里替换成指定穿搭提示词】`

用户可以直接输入完整服装，例如：

```text
穿搭：奶油白细肩带修身迷你连衣裙，胸前立体花朵装饰，搭配奶油白玛丽珍鞋。
```

Skill 必须把该穿搭同步应用到：

- FRONT
- SIDE
- BACK
- 下半部分全部 9 个情绪动作

不要让情绪区随机更换服装。

---

## 6. 固定下半部分：9 组半身情绪动作

所有情绪均为同一人物、同一穿搭、同一发型和同一妆容。

每个情绪动作必须明显不同，不要只是改变嘴角。

### 1｜轻蔑不屑 / Disdainful Contempt

- 微微侧头
- 半眯眼
- 嘴角轻挑
- 双臂抱胸
- 带嫌弃、轻蔑、看不起的感觉
- 视线可轻微偏向侧面，不必直视镜头

### 2｜无奈 / Helpless Exasperation

- 闭眼或轻轻翻白眼
- 双手摊开
- 轻微耸肩
- 一脸“拿你没办法”的感觉
- 身体姿态放松但带明显无奈

### 3｜暗爽得意 / Secretly Pleased

- 嘴角压不住的偷笑
- 一只手轻碰下巴
- 另一只手抱胸
- 眼神偷偷得意
- 可以向侧下方或斜侧方看

### 4｜甜蜜对视 / Sweet Affectionate Gaze

- 温柔看向镜头
- 眼神柔软
- 轻微甜笑
- 双手自然交叠放在胸前
- 姿态自然，不做夸张比心

### 5｜生闷气 / Sulking

- 鼓着脸
- 嘴唇微抿
- 双手抱胸
- 身体稍微转开
- 眼神故意看向旁边
- 明显是生闷气而不是愤怒咆哮

### 6｜委屈撇嘴 / Hurt Pout

- 眉毛内侧压低或轻轻蹙起
- 眼眶微湿
- 嘴角向下
- 轻轻撇嘴
- 一只手靠近嘴边
- 像马上要哭但仍在忍

### 7｜毛骨悚然 / Creeped Out

- 眼睛明显睁大
- 身体缩紧
- 双臂抱住自己
- 肩膀抬起
- 紧张地看向侧后方
- 表情真实，不做鬼脸

### 8｜心虚躲闪 / Guilty Avoidance

- 眼神快速移向旁边
- 不敢直视镜头
- 一只手轻碰脖子或下巴
- 神态慌张、心虚
- 身体可以轻微偏转

### 9｜咬牙切齿 / Gritted-Teeth Anger

- 眉头紧皱
- 咬紧牙齿
- 双手叉腰或自然握拳
- 肩膀紧绷
- 明显愤怒
- 但不过度夸张，不做怪异变形

---

### 7. 眼神方向去重规则

9 个情绪不能全部直视镜头。

建议分配：

- 直视镜头：2–3 个
- 看向左侧：1–2 个
- 看向右侧：1–2 个
- 看向侧后方：1 个
- 看向侧下方：1 个
- 闭眼 / 翻白眼：1 个

眼神方向必须与对应情绪合理匹配。

例如：

- 毛骨悚然 → 看向侧后方
- 心虚躲闪 → 看向侧面
- 无奈 → 闭眼 / 翻白眼
- 甜蜜对视 → 可以直视镜头

---

### 8. 动作去重规则

9 个半身参考动作不能重复。

尤其避免所有动作都变成：

- 双臂抱胸
- 托腮
- 双手放身体两侧
- 全部正面对镜头

必须合理分配：

- 抱胸
- 摊手
- 碰下巴
- 双手交叠
- 身体转开
- 手靠近嘴边
- 抱住自己
- 碰脖子
- 叉腰 / 握拳

每个动作都必须服务于对应情绪。

---

### 9. 人物一致性规则

整张 Character Sheet 必须是同一个人，而不是“长得相似的多人”。

必须保持：

- face identity consistency
- same facial structure
- same eye shape
- same nose
- same lips
- same jawline
- same skin tone
- same hairstyle
- same hair color
- same adult age impression
- same makeup

禁止：

- 不同脸型
- 年龄变化
- 发色变化
- 发型随机变化
- 五官比例漂移
- 随机增加耳环、发饰、项链

---

### 10. 质量控制

默认强化：

- photorealistic adult woman
- Korean editorial character reference
- premium fashion lookbook
- realistic skin texture
- realistic hair strands
- realistic fabric texture
- natural hand anatomy
- natural body proportions
- clean studio layout
- full-body framing
- consistent identity
- consistent outfit
- distinct expressions
- varied gaze direction

避免：

- extra fingers
- fused fingers
- duplicated hands
- duplicated limbs
- malformed anatomy
- cropped feet
- cropped hands
- repeated pose
- duplicated person
- face distortion
- strange expression
- random accessories
- outfit drift
- hairstyle drift

---

### 11. 默认输出模板

```text
使用上传的人物参考图作为唯一人物身份参考，人物必须为明确成年女性。严格保持五官、脸型、肤色、发型、发色、妆容、年龄感和整体辨识度一致。

黑色头发盘成低位发髻，两侧自然碎发，白色花朵发饰，珍珠耳坠，精致自然妆容，真人写实，高级韩系时尚写真质感。

浅米白纯色摄影棚背景，柔和均匀布光，高清真实摄影，真实皮肤纹理、头发细节和服装材质，干净高级 Character Sheet / Fashion Lookbook 排版。

上半部分：完整全身三视图，从头到脚完整展示：
正面 FRONT / 侧面 SIDE / 背面 BACK。
三视图必须为同一人物、同一服装、同一发型、同一鞋履、同一比例，站姿自然，服装前后结构准确。

穿搭：
【这里替换成指定穿搭提示词】

下半部分：同一人物、同一穿搭的 9 个半身表情动作参考：
1. 轻蔑不屑
2. 无奈
3. 暗爽得意
4. 甜蜜对视
5. 生闷气
6. 委屈撇嘴
7. 毛骨悚然
8. 心虚躲闪
9. 咬牙切齿

9 个表情必须自然真实、动作明显不同、眼神方向丰富，不全部直视镜头。动作必须与对应情绪一致，脸部不能崩坏，不能诡异，不重复动作，不增加随机饰品。

整体为真人写实、韩系杂志模特参考图、时尚 Lookbook、人物设定集，构图整齐，人物完整，不裁切手脚，不出现多余人物。
```

---

### 12. 常用调用方式

#### 只替换穿搭

```text
使用 Skill 08。
人物继续使用当前参考图。
只替换穿搭为：……
保持三视图和 9 个情绪动作结构不变。
```

#### 替换人物

```text
使用 Skill 08。
将唯一人物参考替换为我上传的新参考图。
服装和 9 个表情动作保持不变。
```

#### 替换部分情绪

```text
使用 Skill 08。
保持三视图和服装不变。
只把第 3、6、9 个情绪替换为：……
其他动作不变。
```

#### 输出模型版本

支持用户要求：

- ChatGPT-Image
- Midjourney
- Flux / SDXL
- 精简省 Token 版
- 纯中文完整版
- English Prompt

---

### 13. 权利与人物保护

使用人物参考图时，应优先使用：

- 本人照片
- 已取得明确授权的人物照片
- 有合法许可的模特素材
- 自有原创角色

不要将未经授权的真人参考图用于冒充本人、虚构代言、误导性商业宣传、色情化、羞辱或可能伤害当事人的场景。

公开发布或商业使用前，请确认肖像权、版权、隐私、平台规则与适用法律。

详细说明见：

`docs/RIGHTS-SAFETY.zh-CN.md`

---

## English

### 1. Purpose

This Skill creates a clean photorealistic Character Sheet using one consistent clearly adult female reference.

Fixed structure:

- top: full-body Front / Side / Back views
- bottom: nine distinct half-body emotion-action references

The Skill is designed for strong identity consistency, outfit consistency, natural anatomy, varied gaze direction, and clearly differentiated emotional acting.

### 2. Default Character

Use the supplied reference image as the only identity source and preserve:

- facial structure
- face shape
- skin tone
- hairstyle and hair color
- adult age impression
- body proportions
- overall recognizability

Default styling:

> Clearly adult young Asian woman, black hair in a low bun, natural loose strands around the face, white floral hair accessory, pearl earrings, refined natural makeup, photorealistic Korean editorial fashion quality.

### 3. Studio Setup

- light cream-beige seamless background
- soft even studio lighting
- high-resolution realistic photography
- realistic skin texture
- realistic hair strands
- realistic fabric rendering
- clean fashion Lookbook / Character Sheet composition

### 4. Top Section — Three Full-Body Views

Show the entire body from head to toe:

- FRONT
- SIDE
- BACK

All three views must preserve the exact same person, hairstyle, accessories, outfit, footwear, proportions, makeup, background, and lighting.

Garment construction must remain accurate between views.

### 5. Outfit Variable

Replace:

`【这里替换成指定穿搭提示词】`

with the user's desired outfit.

Apply the same outfit to all three full-body views and all nine emotion references.

### 6. Nine Built-in Emotion Actions

1. Disdainful Contempt — slight head tilt, narrowed eyes, subtle raised corner of the mouth, arms crossed.
2. Helpless Exasperation — eyes closed or slight eye-roll, open palms, small shrug.
3. Secretly Pleased — suppressed smile, one hand touching chin, other arm folded.
4. Sweet Affectionate Gaze — soft direct gaze, gentle smile, hands naturally folded near the chest.
5. Sulking — puffed cheeks, lips pressed, arms crossed, body turned slightly away, gaze to the side.
6. Hurt Pout — slightly wet eyes, lowered mouth corners, one hand near the mouth, almost crying.
7. Creeped Out — eyes widened, body tightened, arms hugging self, gaze toward the side/back.
8. Guilty Avoidance — gaze shifting sideways, avoiding eye contact, one hand touching neck or chin.
9. Gritted-Teeth Anger — furrowed brows, clenched teeth, hands on hips or lightly clenched fists, shoulders tense.

### 7. Gaze-Direction Rule

Do not make all nine portraits look directly at camera.

Use a varied distribution of direct gaze, left, right, side-back, downward-side, and closed-eye / eye-roll directions.

### 8. Pose-Diversity Rule

Do not repeat the same gesture across the nine references.

Distribute different actions such as crossed arms, open palms, chin touch, hands folded at chest, body turned away, hand near mouth, hugging self, neck touch, hands on hips, or light fists.

### 9. Identity Consistency

Every panel must depict the exact same person, not merely similar people.

Preserve face shape, facial proportions, eyes, nose, lips, jawline, skin tone, hairstyle, hair color, adult age impression, makeup, and overall identity.

### 10. Quality Control

Emphasize:

- photorealistic adult woman
- Korean editorial model reference
- premium fashion lookbook
- realistic skin and hair
- realistic fabric
- natural hand anatomy
- natural body proportions
- clean studio layout
- distinct expressions
- varied gaze direction

Avoid extra fingers, fused hands, duplicated limbs, cropped feet, repeated poses, duplicated people, face drift, hairstyle drift, random accessories, strange facial deformation, or outfit drift.

### 11. Rights & Likeness

Use reference images you own or have permission to use. Do not use unauthorized real-person likenesses for impersonation, false endorsement, misleading commercial claims, sexualization, humiliation, or other harmful contexts.

Before public or commercial use, verify likeness rights, copyright, privacy, platform rules, and applicable law.

See:

`docs/RIGHTS-SAFETY.en.md`
