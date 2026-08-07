# herdsman-issue

Herdsman 的 **Issue-only** 反馈仓库。用于提交 Bug 与产品需求，供产品经理与研发对照处理。

Issue-only feedback repo for **Herdsman**. Report bugs and requirements for product managers and developers.

## 如何提交 / How to report

1. 打开 [New Issue](https://github.com/szStarWave/herdsman-issue/issues/new/choose)
2. 选择最匹配的模板（不要用空白 Issue，除非确实无法归类）
3. 按表单填写；Bug 请尽量附上版本与日志

| 模板 / Template | 用途 / Use when |
| --- | --- |
| Bug (安装/Install) | 安装、启动、更新失败 |
| Bug (推理/Inference) | 模型推理 / Runtime 异常 |
| Bug (应用/App UI) | 桌面应用或 UI 问题 |
| Bug (其他/Misc.) | 其他未覆盖的缺陷 |
| 功能增强 / Enhancement | 新功能或改进建议 |
| 产品需求 / Requirement | 给 PM / 研发的产品需求 |
| 技术调研 / Research | 技术调研跟踪 |
| 重构 / Refactor | 维护者重构跟踪 |

## 日志路径 / Log paths

- `~/.herdsman/log`
- `~/.cache/herdsman/logs`

Windows 示例：`C:\Users\<you>\.herdsman\log`、`C:\Users\<you>\.cache\herdsman\logs`

## 自动清理 / Stale policy

Issue 连续 **60** 天无活动会标记 `stale`；再过 **30** 天仍无活动将自动关闭。带有 `requirement`、`research`、`refactor`、`bug`、`roadmap`、`security`、`help wanted`、`good first issue` 标签的 Issue 会被豁免。

## 测试用例表格

Herdsman牧马人UI功能测试用例.xlsx
