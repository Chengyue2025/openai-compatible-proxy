# openai-compatible-proxy 🚀

> OpenAI兼容API代理 - 一行代码接入免费大模型，低成本AI应用

## 为什么选择我们？

- ⚡ **OpenAI兼容** - 现有代码无需改动
- 💰 **超低价格** - 体验包仅¥9.9 = 50万Token
- 🆓 **免费模型** - GLM-4-Flash / Llama-3.1-8B
- 🔌 **自动发卡** - USDT支付，1-3分钟到账

## 快速开始

```python
import openai

client = openai.OpenAI(
    base_url="https://gold-show-device-sunrise.trycloudflare.com/v1",
    api_key="你的key"
)
resp = client.chat.completions.create(
    model="glm-4-flash",
    messages=[{"role": "user", "content": "你好"}]
)
print(resp.choices[0].message.content)
```

## 定价

| 套餐 | 价格 | Token额度 |
|------|------|-----------|
| 体验包 | ¥9.9 | 50万 |
| 专业包 | ¥49 | 500万 |
| 至尊包 | ¥199/月 | 无限 |

## 立即购买

👉 [https://gold-show-device-sunrise.trycloudflare.com/ai-shop/](https://gold-show-device-sunrise.trycloudflare.com/ai-shop/)

---
**免责声明**：本服务为AI算力中转，不保证模型输出准确性。USDT支付自动发卡，不支持退款。

⭐ 如果对你有帮助，请给个Star！
