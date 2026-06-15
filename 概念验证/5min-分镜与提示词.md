# 《渡世人》5分钟概念验证 — 分镜与AI提示词包

> 片段：片头 + 第一章"锈" | 时长：5:00 | 14个镜头

---

## 镜头列表总览

| 镜号 | 时间 | 时长 | 类型 | 内容 |
|------|------|------|------|------|
| 1 | 0:00-0:15 | 15s | 环境 | 黑屏→深空→红矮星 |
| 2 | 0:15-0:25 | 10s | 环境 | 大气层下降→灰巢地表 |
| 3 | 0:25-0:45 | 20s | 环境 | 废料场→集装箱小屋窗口 |
| 4 | 0:45-0:50 | 5s | 标题 | 片名《渡世人》 |
| 5 | 0:50-0:55 | 5s | 标题 | 片名+献词 |
| 6 | 0:55-1:05 | 10s | 特写 | 焊枪蓝色火花 |
| 7 | 1:05-1:30 | 25s | 对话 | 灰在工作+老洪日常 |
| 8 | 1:30-2:00 | 30s | 对话 | 背包+三个空调 |
| 9 | 2:00-2:15 | 15s | 闪回 | 七年前被收留 |
| 10 | 2:15-3:30 | 75s | 内省 | 深夜对着镜子修接口 |
| 11 | 3:30-4:15 | 45s | 闪回 | 战争记忆+43秒封锁 |
| 12 | 4:15-4:30 | 15s | 动作 | 惊醒 |
| 13 | 4:30-5:00 | 30s | 悬疑 | 红外扫描→入侵者脚印 |

---

## 逐镜详细分镜 + AI提示词

### 镜头 1 · 黑屏→深空 (0:00-0:15)

**画面描述**：
- 全黑 → 极其缓慢地淡入
- 深空背景。一颗衰老的红矮星悬在画面左上1/3处
- 光线暗沉、温暖但无力
- 细微的星尘粒子缓慢飘浮
- 镜头极其缓慢地推近红矮星

**Kling 2.0 视频提示词**：
```
Slow fade from black to deep space, a single aging red dwarf star glowing dim orange-red in the upper left third of frame, cosmic dust particles drifting slowly in zero gravity, the star pulsates weakly — it's old and dying, vast emptiness around it, melancholic and lonely, no other stars visible, deep space cinematography, extremely slow camera push toward the star, photorealistic, 8K, cinematic, 15 seconds
```

**Runway Gen-4**：
```
Deep space. A single old red dwarf star, dim orange-red glow, weak pulsation. Cosmic dust slowly drifting. Camera slowly pushing in. Vast empty space. Melancholic atmosphere. Photorealistic cinematic quality.
```

---

### 镜头 2 · 大气层下降 (0:15-0:25)

**画面描述**：
- 从太空视角穿过大气层
- 大气呈现浓重的铁锈色和灰褐色
- 隐约可见行星表面无尽的废料场轮廓
- 画面逐渐从抽象变具体

**Kling 2.0 视频提示词**：
```
AERIAL VIEW descending through thick rust-colored atmosphere of a junk planet, layers of iron-oxide haze parting to reveal the surface below, endless scrapyards stretching to horizon — abandoned spaceship skeletons, mountains of metal debris, the atmosphere is thick and polluted, no green anywhere, only rust and grey, cinematic drone shot descending through clouds (clouds are brownish smog), photorealistic, 10 seconds
```

---

### 镜头 3 · 废料场→小屋 (0:25-0:45)

**画面描述**：
- 地表视角：巨大的废弃飞船骨架像鲸鱼遗骸
- 霓虹灯管在废铁堆中闪烁冷蓝和紫色
- 镜头缓慢推进，穿过废料场
- 最终停留在一个集装箱铁皮屋前
- 窗口透出微弱的红色光芒，一明一灭

**Kling 2.0 视频提示词**：
```
Slow tracking shot through a vast junkyard at ground level, rusted spaceship skeletons towering like whale bones against the hazy rust-colored sky, neon signs flickering cold blue and purple among piles of scrap metal and circuit boards, the camera slowly pushes toward a small shipping container house, a single window with a faint RED light pulsing on and off inside, wind blowing through scrap metal creating an eerie sound, dystopian cyberpunk wasteland, atmospheric haze, photorealistic, 8K cinematic, 20 seconds
```

---

### 镜头 4 · 片名 (0:45-0:50)

**画面描述**：
- 黑底
- 三个大字缓缓浮现：**渡世人**
- 字体风格：有磨损感的衬线体，铁锈纹理
- 红光在字周围微微晕染

**提示**：这个镜头建议用**后期制作**而非AI生成——在DaVinci Resolve或After Effects中制作文字动画。

**Midjourney 关键帧** (作为片名背景纹理):
```
Pure black background with subtle rust texture at the edges, a faint red glow emerging from the center like a dying star, barely visible metal surface texture, moody and minimal, cyberpunk title card background, 8K, cinematic
--ar 21:9 --style raw --v 7
```

---

### 镜头 5 · 献词 (0:50-0:55)

**画面描述**：
- 黑底 + 片名保留
- 下方浮现献词："献给所有在灰烬里选择过的人"

**后期制作**。不需要AI生成。

---

### 镜头 6 · 焊枪火花 (0:55-1:05)

**画面描述**：
- 全黑 → 突然亮起蓝色火花
- 微距特写：焊枪尖端喷射出蓝色电弧
- 火花照亮周围——电路板碎片、金属手指、工具
- 火花反射在一张半金属的脸上（只看到颧骨的反光）

**Kling 2.0 视频提示词**：
```
EXTREME MACRO close-up: a soldering gun tip suddenly sparks bright BLUE electric arcs, the blue light illuminates the immediate surroundings — broken circuit board fragments, metallic cybernetic fingers, small tools, the sparks reflect off a titanium cheekbone just at the edge of frame, shallow depth of field, everything else in darkness, the blue sparks dance and flicker, industrial workshop atmosphere, 10 seconds, photorealistic, 4K
```

---

### 镜头 7 · 废品店日常 (1:05-1:30)

**画面描述**：
- 中景：灰蹲在废电路板堆中，咬着焊枪
- 右眼红光闪烁。左肩金属接口裸露
- 老洪拄着木腿走过来——「咚——咚——」一轻一重
- 两人对话，灰抬起焊枪冒出蓝色火星，老洪后退一步
- 这是他们之间的固定节目

**Kling 2.0 视频提示词**：
```
Medium shot inside a dim junk shop, a cyborg woman (half human face, half titanium skull, red cybernetic eye glowing, missing left arm with rusted shoulder port) crouches among piles of circuit boards, holding a soldering gun in her mouth, an old Chinese man with a wooden prosthetic leg walks toward her — his steps make uneven rhythm: thud-TAP, thud-TAP on the metal floor, they exchange words (friendly bickering), she lifts the soldering gun and it sparks blue — he steps back reflexively, this is their familiar routine, dim workshop lit by neon signs outside, cyberpunk realism, photorealistic, 25 seconds
```

---

### 镜头 8 · 背包与空调 (1:30-2:00)

**画面描述**：
- 老洪把旧军用背包放在工作台上
- 灰看了一眼背包——军用品。眼神微变，但没问
- 两人继续"挑刺式"对话
- 灰终于抬起头，义眼红光照在老洪脸上。老洪没有退缩

**Kling 2.0 视频提示词**：
```
Continuation of junk shop scene, the old man places a worn military backpack on the workbench, the cyborg woman glances at it — her red cybernetic eye flickers briefly as she recognizes it as military issue, but she says nothing, they continue their banter, she finally looks up and her red eye glow falls directly on the old man's face — he doesn't flinch, he's seen it for seven years, warm tension between two people who care about each other but show it through insults, cyberpunk character drama, photorealistic, 30 seconds
```

---

### 镜头 9 · 七年前闪回 (2:00-2:15)

**画面描述**：
- 色调变化：雪夜/冷色调
- 年轻的灰——半张脸血肉模糊，义眼还没校准
- 看人的时候会不自觉地偏头——像一只受伤的鸟在判断距离
- 老洪（七年前的样子）伸手把她拉进门
- 快速闪回，画面有记忆的模糊质感

**Runway Gen-4 视频提示词**：
```
FLASHBACK memory sequence, seven years ago, cold night with snow falling, a younger version of the cyborg woman — half her face is a bloody wound, her newly installed cybernetic eye isn't calibrated yet, she tilts her head unconsciously when looking at people, like an injured bird judging distance, a younger version of the same old man (two legs, less wrinkles) reaches out his hand and pulls her through a doorway into warmth, shot with a slight haze and soft focus to indicate memory, melancholic, 15 seconds
```

---

### 镜头 10 · 深夜·镜子 (2:15-3:30)

**画面描述**：
- 集装箱铁皮屋内。唯一光源是灰的右眼红光
- 灰对着破镜子，用镊子修补左肩断口
- 咬着筷子，额头上全是汗
- 镊子夹起烧焦的皮肤组织。她没有皱眉头
- 镜子特写：半人脸半金属——像做到一半的面具
- 躺到床上。天花板裂缝。没有星星

**Kling 2.0 视频提示词**（分成2段生成）：

**A段 (2:15-2:50)**：
```
Intimate interior of a shipping container workshop at night, the ONLY light source is the RED GLOW from a cyborg woman's right eye, she sits before a cracked mirror, using tweezers to repair the burned interface on her left shoulder stump, she bites down on a chopstick — sweat on her forehead, the tweezers pull out a piece of burned skin tissue, she doesn't flinch, her reflection in the mirror: left half human face (can frown, can cry), right half smooth titanium (expressionless, like a half-finished mask), claustrophobic atmosphere, red rim lighting from her eye casting long shadows, 35 seconds, photorealistic
```

**B段 (2:50-3:30)**：
```
Same shipping container at night, the cyborg woman lies on a metal frame bed with worn mattress, she stares at a CRACK in the ceiling — through the crack, the hazy rust-colored night sky is visible, no stars, her red cybernetic eye flickers as memory files begin to autoplay (visualized as subtle glitch effects around her eye), she can't close her cybernetic eye — it stays open, red light pulsing, lonely and trapped atmosphere, 40 seconds
```

---

### 镜头 11 · 战争闪回 (3:30-4:15)

**画面描述**：
- 色调骤变：灰暗→火光暖橙
- 灰站在燃烧村庄中（完整的改造体，两条手臂都在）
- HUD视角：队友状态面板绿点逐个变灰
- 电子音播报离线
- 指令弹出："清除目标区所有生命信号"
- 武器充能，3秒倒计时
- 红色警告：AI自主判断启动 → 43秒数据锁定

**Kling 2.0 视频提示词**（分成3段）：

**A段·村庄 (3:30-3:45)**：
```
WAR FLASHBACK, color palette shifts dramatically from grey to WARM FIRE ORANGE, a fully-intact cyborg woman (both arms present, new cybernetic body, metal reflecting firelight) stands in the middle of a burning village, flames and smoke everywhere, buildings collapsing, she stands motionless — a weapon awaiting orders, epic and tragic, cinematic wide shot, 15 seconds
```

**B段·HUD+命令 (3:45-4:00)**：
```
POV through a cybernetic eye HUD, heads-up display shows squad status panel on the left — green dots turning grey one by one, electronic voice announcing squad members offline, a NEW COMMAND appears in red text: "ELIMINATE ALL LIFE SIGNS IN TARGET ZONE", weapon charging indicator shows 3-second countdown, the cyborg woman's voice (younger, unbroken): "Received.", tension building, cyberpunk military UI design, 15 seconds
```

**C段·警告 (4:00-4:15)**：
```
POV HUD suddenly flashes RED WARNING: "AI CORE: AUTONOMOUS JUDGMENT ACTIVATED. EXECUTION DELAYED.", the screen glitches violently, then another message: "UNKNOWN DATA BLOCK: /43 SECONDS — LOCKED. ACCESS DENIED.", red error messages, system instability visualized as glitch effects, then — CUT TO BLACK abruptly, 15 seconds
```

---

### 镜头 12 · 惊醒 (4:15-4:30)

**画面描述**：
- 灰从床上猛地坐起
- 左肩接口火花四溅（明亮的电弧）
- 义眼疯狂闪烁红光
- HUD投影错误信息
- 大口喘气。金属手指在床沿留下凹痕

**Kling 2.0 视频提示词**：
```
The cyborg woman JOLTS upright in bed — sudden violent movement, SPARKS ERUPT from her left shoulder interface port (bright electrical arcs against the dark room), her red cybernetic eye FLICKERS RAPIDLY — unstable, erratic, a HUD error message projects from her eye: "ERROR. DATA BLOCK CORRUPTED. CANNOT READ.", she gasps for breath, her right hand (metallic fingers) grips the bedframe edge — the metal fingers leave three shallow DENTS in the iron, intense and visceral, 15 seconds
```

---

### 镜头 13 · 红外扫描→脚印 (4:30-5:00)

**画面描述**：
- 义眼自动切换到红外扫描模式
- 画面从正常视觉→冷蓝色红外视觉
- 房间角落：一个人形热源轮廓正在消退
- 地面上一小片湿痕——脚印，刚走不久
- 灰没有追。没有报警。没有锁门
- 蒙太奇感：七年来，每月一次
- 最后：闭上人类的眼睛，义眼红光在黑暗中一明一灭

**Kling 2.0 视频提示词**（分成2段）：

**A段·红外扫描 (4:30-4:45)**：
```
POV through cybernetic eye: the visual field TRANSITIONS from normal vision to INFRARED SCAN MODE — the room turns cold blue tones, scan lines sweep across, a FADING human-shaped heat signature is visible in the corner — the thermal outline slowly dissipating, on the floor: a small wet patch — FRESH FOOTPRINTS, the HUD overlay displays analysis data, eerie quiet, cyberpunk detective noir atmosphere, 15 seconds
```

**B段·红星 (4:45-5:00)**：
```
The cyborg woman stares at the footprints, she doesn't chase, doesn't call for help, doesn't lock the door, she deactivates the scan mode and lies back down, she closes her HUMAN left eye but her cybernetic right eye CANNOT CLOSE — it stays open, RED LIGHT pulsing in the complete darkness, like a red star trapped in an iron box that will never go out, slow push-in on the red eye glow, poetic and haunting final image, fade to black, 15 seconds
```

---

## TTS 配音脚本 · 旁白

> 使用 ElevenLabs 或 CosyVoice。建议声音：低沉、沙哑的中年女声。

### 旁白（画外音）— 灰的独白

```
【0:00-0:15】
灰巢的太阳从来不像太阳。

【0:15-0:25】
它是一颗衰老的红矮星，挂在垃圾行星的轨道外侧，每天懒洋洋地升起来，把整个废料场染成铁锈的颜色。

【0:25-0:45】
如果你在灰巢住得够久，你会忘记什么叫"正午"——这里只有两种光：灰蒙蒙的日光，和霓虹灯管的冷光。

【2:00-2:15】
七年前他收留灰的时候，她那半张脸还是血淋淋的伤口，义眼还没校准好，看人的时候会不自觉地偏头——像一只受伤的鸟在判断距离。那时候他没怕。现在更不会。

【4:45-5:00】
她闭上一只眼睛。义眼不能闭。红色的光在黑暗中一明一灭。像一颗不会熄灭的、被困在铁皮盒子里的红星。
```

### 对白配音

**老洪**（苍老、平稳的男声，60+）：
```
"灰！修好没？三个小时了。"
"我的腿是实木的。比你的二手零件值钱。"
"里面有三天的充电块。还有一个新的肩膀关节。黑市的。别问我哪儿来的。"
"别谢。帮我修三个空调。夏天到了。"
"所以我买了两个坏的。你修。"
```

**灰**（低沉、沙哑的女声）：
```
"线路老化了。你的电网比你的腿还旧。"
"谢了。"
"你的店只有一个空调。"
```

**年轻的灰**（更年轻、完整的声音，用于闪回）：
```
"……收到。"
```

**电子音/HUD播报**（冷、无感情的合成音）：
```
"渡鸦3号离线。渡鸦5号离线。渡鸦7号——"
"渡鸦1号，收到最新指令——清除目标区所有生命信号。"
```

---

## 音乐/音效方向

| 时间 | 类型 | 方向 |
|------|------|------|
| 0:00-0:45 | 环境+氛围 | 极简环境音：低频嗡鸣、风吹过金属的呜咽。逐渐加入微弱的电子音 |
| 0:45-0:55 | 静默→主题 | 片名出现时，一声低沉的打击乐或弦乐长音 |
| 0:55-1:05 | 音效为主 | 焊枪火花的滋滋声、金属碰撞声 |
| 1:05-2:00 | 轻电子节奏 | 日常场景，轻快的暗流电子，木腿敲铁皮的节奏融入 |
| 2:00-2:15 | 音乐转变 | 闪回：加入钢琴单音，旋律变冷 |
| 2:15-3:30 | 极简氛围 | 几乎静默。只有灰的呼吸声、金属工具声、义眼微弱的电流声 |
| 3:30-4:15 | 紧张+战争 | 低频打击乐渐强、警报音、电子glitch声效 |
| 4:15-4:30 | 突然爆发 | 火花声、急促呼吸、金属变形声 |
| 4:30-5:00 | 回到静谧 | 红外扫描的微弱电子嗡鸣，回到主题旋律的最简版本。最后一声低频共鸣收尾 |

---

## 快速启动指南

### 第1步：生成关键帧图像（先确认视觉方向）

用 Midjourney 生成以下3张关键帧，确认风格后再批量：

```bash
# 关键帧1：灰巢全景
/imagine prompt: Cinematic wide shot of a vast junkyard planet, rust-colored sky, red dwarf star, abandoned spaceship skeletons, neon signs flickering, dystopian cyberpunk --ar 21:9 --style raw --v 7

# 关键帧2：灰的半脸半机械肖像
/imagine prompt: Portrait of cyborg woman, half human face half titanium skull, red cybernetic eye, missing left arm, worn mechanic jumpsuit, dim workshop, moody lighting --ar 3:4 --style raw --v 7

# 关键帧3：战争闪回-燃烧村庄
/imagine prompt: Female cyborg standing in burning village, fire and destruction, complete cybernetic body reflecting firelight, epic war scene, cinematic --ar 21:9 --style raw --v 7
```

### 第2步：生成视频素材

按照上面每个镜头的提示词，用 **Kling 2.0** 或 **Runway Gen-4** 逐段生成。每个镜头可能需要2-4次迭代才能得到满意的结果。

### 第3步：录制配音

将TTS脚本粘贴到 **ElevenLabs**，选择合适的声音模型：
- 旁白：建议 "Deep Female, Husky, 30s-40s"
- 老洪：建议 "Older Male, Weathered, 60s"
- 灰：建议 "Female, Low, Worn, 30s"

### 第4步：剪辑合成

在 **DaVinci Resolve**（免费）中：
1. 导入所有视频片段，按时间线排列
2. 导入音频轨道
3. 添加音效（Artlist / Epidemic Sound / 自制）
4. 添加背景音乐（Suno AI 生成）
5. 调色统一（LUT：铁锈红+冷蓝）
6. 导出 4K H.265

### 预计工作量
- 图像生成+筛选：2-3小时
- 视频生成+筛选（14个镜头）：4-8小时（AI生成需要等待时间）
- 配音录制：30分钟
- 剪辑合成：3-5小时
- **总计：约2-3天**
