# money —— 基金投资组合项目（真实持仓）

本仓库用于跨设备同步 NingKaiCoo 的基金投资分析项目（真实资金回本作战）。

## 文件导航（按阅读优先级）

| 文件 | 角色 | 说明 |
|---|---|---|
| `fund-analysis/reports/每日作战手册.html` ⭐ | **活规则·核心** | 现行所有有效规则、闸门、信号、对齐锚点格式——**唯一权威源**，决策以它为准 |
| `fund-analysis/reports/资金策略复检.html` | 历史档案 | 方案 B（速度优先）决策论证；细则已落地手册第 4/8 节 |
| `fund-analysis/reports/最初持仓诊断.html` | 历史档案 | 2026-08-06 初诊，结论（100% 科技失衡）已被方案 B 覆盖 |
| `fund-analysis/reports/每日操作.md` | 操作流水 | 每日余额双栏（持仓市值 / 可操作余额）+ 核心判定 |
| `fund-analysis/reports/经验教训总结.md` | 经验库 | L1–L10 反面教训 + G1–G9 正面经验 + 每周复盘结论，按需查阅 |

> `周度复盘报告_2026-08-03_08-07.html` 已于 2026-08-12 删除——其结论（操作流水 / 每周结论 / 规则优化）均已并入上表文件，无信息损失。

## 跨设备同步

克隆（用本机桌面 `GitHub同步令牌_NingKaiCoo_money.txt` 里的 PAT）：

    git clone https://<你的PAT>@github.com/NingKaiCoo/money.git

日常：

    git pull
    git add -A
    git commit -m "..."
    git push

> 注意：GitHub 会自动扫描仓库中的明文 PAT 并可能吊销，token 仅存本机，勿提交进仓库。
> 本仓库含真实持仓与分析，仅限本人设备同步使用。
