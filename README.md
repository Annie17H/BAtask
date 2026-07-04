# 江西铜业 A股 vs 港股 交易数据分析

本项目通过 Tushare Pro 获取江西铜业 A股 (600362.SH) 和港股 (00358.HK) 近一年的日线交易数据，进行可视化展示和对比分析。

## 在线访问

- **A股单股面板**: https://annie17h.github.io/BAtask/jxty_dashboard.html
- **AH对比分析面板**: https://annie17h.github.io/BAtask/jxty_compare.html

## 文件说明

| 文件 | 说明 |
|------|------|
| `outputs/jxty_dashboard.html` | A股 K线图 + 成交量 + 技术指标面板 |
| `outputs/jxty_compare.html` | A股 vs 港股 对比分析面板 |
| `outputs/jxty_600362_A.csv` | A股日线数据 (242个交易日) |
| `outputs/jxty_00358_HK.csv` | 港股日线数据 (245个交易日) |
| `outputs/jxty_AH_compare.csv` | AH同期对比数据 (含溢价率) |
| `outputs/jxty_data.json` | A股数据 JSON 格式 |
| `outputs/echarts.min.js` | ECharts 图表库 (本地引用) |

## 数据来源

- **Tushare Pro**: https://tushare.pro
- **数据范围**: 2025-07-04 ~ 2026-07-03

## 技术栈

- 图表: ECharts 5.5.0
- 数据: Tushare Pro MCP / Python SDK

## 免责声明

本数据仅供参考，不构成投资建议。投资有风险，决策需谨慎。
