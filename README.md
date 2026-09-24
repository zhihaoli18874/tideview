# 观潮 TideView

<img src="assets/tideview-logo-mark.svg" width="52" alt="观潮 TideView 标志" />

**多市场交易研究，一个工作台。** 观潮 TideView 把行情图表、技术分析和复盘记录放在一起，帮助个人投资者在不同市场之间切换观察，减少来回打开多个看盘软件。

**中国大陆可直接使用，无需翻墙。** 在国内网络即可访问观潮官网、打开 Web 版或下载客户端。

[了解产品](https://guanchaotv.com/product/) · [打开 Web 应用](https://guanchaotv.com/app/) · [官网下载](https://guanchaotv.com/download/) · [常见问题](https://guanchaotv.com/faq/)

> **关于这个仓库**：这里公开的是产品介绍、使用说明、策略示例和反馈入口。观潮的客户端、服务端及行情处理源码没有在此发布；本仓库不是开源软件仓库。详见 [版权与使用说明](NOTICE.md)。

## 产品介绍视频

33 秒了解观潮如何把多市场行情、图表分析和复盘放在一个工作台。

https://github.com/user-attachments/assets/f9336f6a-df1f-440d-bf7a-58ebda24f82a

[下载原版 MP4](assets/tideview-product-intro.mp4)

## 覆盖市场

| 市场范围 | 可观察的市场 |
| --- | --- |
| 基础市场 | A 股、港股、国内期货 |
| 全球市场（旗舰版） | 美股、韩股、外汇、加密货币、贵金属 |

**一个工作台看多市场，少在不同软件之间来回切换。** 各市场具体可用的标的、行情数据和功能，以当前产品界面及会员说明为准。

## 可以用它做什么

| 场景 | 研究任务 | 可使用的工具 |
| --- | --- | --- |
| 盘前 | 整理自选、观察市场与板块 | 行情图表、自选、筛选 |
| 盘中 | 跟踪价格结构和预设观察条件 | 多周期 K 线、指标、画线、预警 |
| 盘后 | 记录判断依据与待验证条件 | 复盘工作台、交易记录、明日计划 |

这里有一份不依赖买卖结论的 [研究流程示例](docs/research-workflow.md)。具体功能和开放范围以当前产品界面为准。

## 策略脚本示例

想自己研究策略，可以从三份观潮内置 Pine v5 示例开始：[均线交叉](examples/strategies/ema-crossover.pine)、[MACD 信号交叉](examples/strategies/macd-crossover.pine)、[RSI 超买超卖](examples/strategies/rsi-rebound.pine)。每份都提供可复制的源码和可在脚本编辑器中导入的 JSON 文件；见[下载、导入与使用说明](examples/strategies/README.md)。脚本编辑器和策略回测的可用范围以当前会员权益为准。

**欢迎分享你写的好用策略脚本！** 请通过[策略脚本投稿](https://github.com/zhihaoli18874/tideview/issues/new/choose)提交原创脚本、思路和适用场景。投稿前请移除个人信息与密钥，并确认你有权允许公开展示和学习使用。用户在应用脚本广场公开的脚本不会自动搬到这个仓库。

## 开始使用

1. 在浏览器中[打开观潮](https://guanchaotv.com/app/)，或从[官网下载页](https://guanchaotv.com/download/)获取当前可用的客户端。
2. 从熟悉的市场和标的开始，先看图表与周期，再按需要加入指标和画线。
3. 把观察事实、自己的解释及后续验证条件分别记录下来，避免把分析结果直接当成交易指令。

## 反馈

欢迎通过本仓库的 **Issues** 提交可复现的产品问题或使用建议。提交前请移除账号、联系方式、持仓、交易记录、令牌及其他私密信息。账户和支付问题请使用[官网帮助入口](https://guanchaotv.com/faq/)。

## English

TideView is a trading research workspace for individual investors. It can be accessed and used from mainland China without a VPN. Explore mainland China stocks, Hong Kong stocks, and domestic futures alongside US and Korean stocks, forex, crypto, and precious metals in one workspace. Global markets require the Ultimate plan. Market data and feature availability vary. This public repository contains product information, strategy examples, and feedback resources; the application and service source code remain proprietary.

---

观潮 TideView 提供的行情、指标、AI 分析、回测、选股、盘口和复盘内容仅供学习研究和辅助决策参考，不构成任何投资建议、证券咨询或投资顾问服务。市场有风险，投资需谨慎。
