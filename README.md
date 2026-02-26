# ₿ 比特币四年周期模型 / Bitcoin 4-Year Cycle Model

一个简洁的单页应用，可视化展示比特币减半周期规律。

A minimal single-page app visualizing Bitcoin's halving cycle pattern.

## 📊 功能 / Features

- **减半倒计时** / Halving countdown — 实时显示距下次减半的剩余时间
- **当前阶段** / Current phase — 自动判断当前处于周期中的哪个阶段，附带进度条
- **完整时间线** / Full timeline — 展示 48 个月完整周期的 5 个阶段

## 🔄 减半 T0 模型 / Halving T0 Model

以减半月份为 T0：

| 阶段 Phase | 时间 Period | 说明 Description |
|---|---|---|
| 震荡阶段 Consolidation | T+0 ~ T+12 | 市场消化供给变化，后期上升启动 |
| 主升浪 + 见顶 Main Rally | T+12 ~ T+18 | 最容易出现主升浪，见顶均值 T+16 |
| 高位转弱 Weakening | T+18 ~ T+24 | 趋势转弱，转向熊市的转弯阶段 |
| 熊底窗口 Bear Bottom | T+24 ~ T+30 | 历史熊底窗口，统计均值 T+28 |
| 修复期 Recovery | T+30 ~ T+48 | 缓慢修复，准备进入下一轮减半 |

## 🚀 使用 / Usage

纯静态 HTML，无需任何依赖，直接打开即可：

Zero dependencies, just open the file:

```bash
open index.html
```

在线访问 / Live: [https://xwzp.github.io/btc-cycle/](https://xwzp.github.io/btc-cycle/)

## ⚠️ 免责声明 / Disclaimer

本工具基于历史周期统计规律，仅供参考，不构成任何投资建议。

This tool is based on historical cycle patterns for reference only. It does not constitute investment advice.

## 📜 License

MIT
