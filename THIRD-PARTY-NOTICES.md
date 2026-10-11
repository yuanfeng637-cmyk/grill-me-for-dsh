# 第三方声明与许可

本技能包含两部分权利内容，分发时**两部分都要随附**。

---

## 1. 直接复用（MIT，必须随附）

五维 0–1 rubric、各维锚点示例、阈值数字（spec 0.2 / ticket 0.3 / freeform 0.4）、聚合＝均值的定义、退出报告格式、评分纪律骨干，**逐字（中文翻译）复用**自：

- 仓库：https://github.com/max4c/skills
- 路径：`skills/grill-me/SKILL.md`
- 内容标识：git blob `5c1067b862fb1de4ef9546e817a5a1b3984989a3`（10,391 bytes），2026-10-11 抓取

其许可全文与版权声明如下（同时逐字保留在 `SKILL.md` 末尾）：

```
MIT License

Copyright (c) 2026 Max Forsey

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 2. 仅作功能点 / 结构参考（未复制其表达）

| 来源 | 许可状态 | 参考了什么 |
|---|---|---|
| https://github.com/RobMitt/grill-me-skill | **仓库无 LICENSE**（默认保留所有权利） | "每题必经选择式提问工具、2–4 个具体选项、一次一问、能查就别问"这组功能点 |
| https://github.com/matt-riley/agent-skills → `skills/grill-me` | **GPL-3.0**（v2.0.1） | "何时用/何时不用 + 防线 + 自检"这组结构位置 |
| https://github.com/EricTechPro/grill-me-checkpoint | **MIT** | checkpoint 契约功能点（"文件才是事实来源"、每人答一条、open flag 带责任人、收尾重读消解矛盾） |

**列示来源不表示获得额外复制授权。** 2026-10-11 做过一次逐句表达比对，发现并改写了四处与上游重合的表述（两处英文短语逐字相同、两处中文对应句）；比对覆盖本技能全文与所取到的上游原文/节选，**未核验上游完整仓库与历史版本**，且该比对是文本审查结论，**不构成法律裁定**。若上述作者对处理方式有异议，请提出，会立即改写或删除对应部分。

---

## 3. 本项目的授权

本项目**新增部分**（运行环境与操作边界、checkpoint 契约、账目与备份纪律、无落盘模式、中途变更、评分快照、退出优先级、报告模板与自检等）由本项目作者以 **MIT** 授权，见 `LICENSE`。基座部分的 MIT 条款与 `Copyright (c) 2026 Max Forsey` **不得移除**。

> 说明：仓库根 `LICENSE` 只保留**纯 MIT 文本**（`Copyright (c) 2026 yuanfeng637-cmyk` + 标准条款），
> 以便 GitHub 等平台自动识别为 MIT；基座署名、逐字复用清单与全部第三方说明**以本文件为准**，
> 与本 `LICENSE` 具有同等效力、**不得移除**。
