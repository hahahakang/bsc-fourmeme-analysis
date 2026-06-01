# BSC Four.meme 交易员链上分析

这是一个用于 GitHub Pages 的静态分析站点。

## 内容

- `index.html`: 线上报告首页
- `data/buy_detail_with_fdv.csv`: 每笔买入明细，含买入时间、token、买入 FDV、池子流动性估算
- `data/token_trade_summary.csv`: token 级汇总
- `data/fdv_bucket_summary.csv`: 买入市值分桶结果
- `data/top_winners.csv`: 最大盈利样本
- `data/top_losers.csv`: 最大亏损样本
- `downloads/bsc_blogger_trade_analysis.xlsx`: 完整 Excel 工作簿

## 口径说明

买入市值为链上成交价乘以 token 总供应量的 FDV 近似口径，不等于严格流通市值。

收益为已匹配 Four.meme 交易的链上现金流，未对未卖出的残余持仓做当前价格标记。

本仓库不包含 RPC receipt 缓存、原始 BscScan CSV 和其他较大的中间文件。
