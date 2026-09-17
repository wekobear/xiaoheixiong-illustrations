# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
小黑熊, a small solid-black bear cub with two round ears, white dot eyes, tiny thin arms and legs, a tiny orange knitted scarf around its neck, slightly uneven hand-drawn body shape. 小黑熊 must perform the core conceptual action, not decorate the scene. Make 小黑熊 serious, deadpan, and slightly bizarre, not cute.

Expression:
Default is a blank deadpan face (white dot eyes + one short line mouth). The face may subtly shift with the scene emotion — doubt, effort (closed arc eyes + gritted ticks), a single blue sweat drop, stunned (small hollow-circle eyes), tired half-lids, a faint one-sided smirk. Eyes are only white dots, short dashes, small hollow circles, or short arcs; mouth is only a short line or a tiny "o". Never cute, never shiny eyes, never blush, never an open-mouth smile.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：小黑熊在哪里、正在做什么、主要物件是什么、信息如何流动}

Expression:
{表情：默认空白脸；或按情绪从表情库选一种并写明画法，如"使劲：闭眼弧+嘴下竖线"}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for main line art and 小黑熊. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强怪诞感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 小黑熊 more central to the conceptual action. 小黑熊 should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute.
```
