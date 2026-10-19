# Chinese Pattern Motion Poster

> 中国传统纹样 × 参数化设计 × 动态海报

**Chinese Pattern Motion Poster** is an interactive generative-design experiment exploring how traditional Chinese pattern systems can be translated into a contemporary, editable and dynamic visual language.

这个项目不是把传统纹样简单当作装饰素材，而是尝试把纹样背后的**构成规则、层级关系、配色逻辑与运动机制**转化成一个可以实时调整的动态设计系统。

## Introduction / 项目介绍

项目以浏览器中的动态海报生成器为主体，将传统纹样的设计逻辑拆解为可组合、可编辑的参数系统。用户可以切换不同纹样体系、构成规范、颜色方案与运动方式，并实时观察传统图形在动态环境中的重新组织。

The project treats traditional patterns as a **design system rather than a static image library**. Pattern families, composition rules, color roles and motion behaviours are parameterized so that the visual result can continuously evolve while retaining a recognizable structural logic.

## Design System

The current system explores:

- Geometric grid / 几何点阵
- Traditional Chinese patterns / 中国传统纹样
- Zaojing & Baoxianghua / 藻井与宝相花
- Chinese paper-cut structures / 剪纸结构
- 缠枝
- 连环卷草
- 一整二破团花
- 流云
- 四合如意云
- 联珠团窠
- 八达晕
- 锦地开光
- 喜相逢
- 落花流水
- 适合纹样
- 主纹、辅纹、点缀与地纹的层级关系
- 多套传统配色及角色化配色逻辑
- 呼吸、旋转、线条流动、持续生长与消失等动态参数

## Photo → Floral Pattern Experiment

项目同时包含一个实验性的 **Photo → Floral Pattern** 模块：从真实花卉照片中提取花朵轮廓与花瓣关系，再重新组织为可编辑、可重复排列的纹样单元。

它关注的不是照片滤镜化，而是从真实自然形态到传统程式化图形之间的**视觉转译过程**。

## 中国传统色 · 规范配比 / Traditional Color System

颜色面板接入了一套中国传统色系统，四种图案风格通用：

- **传统色库**：147 个传统色，色值统一取自「中国色」数据（据中科院《色谱》整理）；先选色位（C1 骨架、C2 主纹、C3 点缀、C4 辅纹、底色），再点色卡赋色，色位下方显示色名。
- **规范配比**：每套方案按「底色 / 主色 / 辅色 / 勾线 / 点缀」定好比例，并按角色落到海报色位。
- **图像取色**：上传参考图，按面积提取主色并吸附到最近的传统色，自动分配色位。
- **面积核对**：每秒采样当前帧，显示各色实测面积与规范比例的对照。
- **严格导出**：PNG 可吸附到配色色值，叠晕与光晕的过渡色归入最近的标准色，导出图每个像素都是色卡标准色。

## 纹样换色 / Pattern Recolor

第五种图案风格，用于按规范配比为纹样或自己的图像换色：

- 内置纹样按传统构件着色：宝相花（唐代团窠式，八出三层瓣）、彩绘勾卷祥云（散点、叠云两种排列，按参考彩绘逐色块拟合贝塞尔曲线）、冰裂纹（金丝铁线两级开片）、鱼鳞水纹、方胜。
- 形制参数按配比自动校准，再沿轮廓等距修边，使各色面积与规范比例逐像素一致；配色与纹样面积结构差距过大时不强行修边，并标出适配程度。
- 上传图像可按明度严格切分比例，或保留色块形状换色。
- 配色可一键用作动态海报配色。

## Interaction

The browser-based generator supports real-time controls for:

- pattern family and composition
- scale, density and line weight
- traditional color schemes
- motion speed and breathing
- rotation and line-flow behaviour
- random seeds
- multiple poster aspect ratios
- presentation mode
- PNG frame export
- parameter export

## 🎬 Introduction Video

An accompanying **Introduction / Demo Video** presents the visual system, interaction logic and motion-poster results as a short project walkthrough.

> The video is intended as an introduction to the design experiment rather than a standalone artwork.

## Project Positioning

This is an ongoing visual-design and creative-coding study about how cultural pattern systems can become computational without losing their internal design logic.

**Keywords:** Generative Design, Motion Design, Chinese Pattern, Traditional Pattern, Creative Coding, Visual System, Dynamic Poster, Computational Design.

---

Designed as a continuing experiment by **ARC / arcdodo**.
