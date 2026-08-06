# money —— 基金投资组合项目（真实持仓）

本仓库用于跨设备同步 NingKaiCoo 的基金投资分析项目。

## 内容
- `fund-analysis/reports/`：投资组合诊断、8 月计划、每日作战手册、回撤计划、资金复盘等 HTML 报告
- `.workbuddy/memory/`：项目会话记忆（策略、规则、持仓演变）

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
