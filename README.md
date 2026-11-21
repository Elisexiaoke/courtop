# cour.top — AI API 中转站

GPT / Claude / Grok / DeepSeek 四条线一个站搞定，香港节点，标准兼容接口。

站点：https://cour.top
图文接入教程：https://cour.top/guide/
官方 QQ 交流群：**1128765545**（充值问题、配置答疑、最新通知都在群里同步）

**新用户注册即送 ¥5 体验额度**，注册后自动到账，全部模型都能试。

## 价格

| 产品线 | 倍率 | 说明 |
| --- | ---: | --- |
| GPT | 0.5 倍率 | 官方价一半 |
| DeepSeek | 0.38 倍率 | |
| Grok | 0.28 倍率 | |
| Claude | 站内可查 | 每个模型的价格在站内「模型广场」公开 |

充值 1:1，付 1 元得 1 美元额度。按量计费，余额不过期，不扣月费。用量和余额在后台随时可查。

## 支持的模型

- GPT：gpt-6.1-sol（主力）、gpt-6.2-sol、gpt-6-sol、gpt-6-luna、gpt-5.4-mini
- Claude：claude-sonnet-5、claude-opus-5-5、claude-haiku-4-5
- Grok：grok-4.5、grok-4.7、grok-4.6、grok-4.3
- DeepSeek：deepseek-v4-pro、deepseek-v4-flash

## 快速开始

1. 在 https://cour.top 注册并登录（¥5 体验额度自动到账）
2. 在「API 密钥」页按你要用的分组创建密钥（不同分组的密钥不能混用）
3. 把 API 地址和密钥填到你的客户端里，模型 ID 照教程里的总表填

API 地址：https://api.cour.top

## 支持的客户端

Codex、Claude Code、WorkBuddy、Cherry Studio、Chatbox、Cursor 都有带图的图文教程，其他支持自定义 API 地址的 OpenAI 兼容客户端也能接：

https://cour.top/guide/

## 说明

- Claude 这条线是双上游互备，一家出问题自动切到另一家，不用手动换地址
- 常见问题：401 一般是密钥填错或密钥与模型不属于同一分组；404 / 模型不存在一般是模型 ID 填错，照教程末尾的总表核对即可
- 有问题可以在本仓库提 Issue，或加 QQ 群 1128765545

---

## English

cour.top is an AI API gateway (Hong Kong node) offering GPT, Claude, Grok and DeepSeek models through one OpenAI-compatible endpoint.

- GPT at 0.5x official pricing, DeepSeek 0.38x, Grok 0.28x; Claude pricing is listed publicly on the site's model plaza
- Top up 1:1 (pay ¥1, get $1 of credit), pay-as-you-go, balance never expires
- New accounts get ¥5 of free trial credit on signup
- Works with Codex, Claude Code, Cursor, Cherry Studio, Chatbox and any OpenAI-compatible client
- Setup guide with screenshots: https://cour.top/guide/
