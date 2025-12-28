# AronAI 使用指南

## 1. 配置 API 端点
AronAI 现在支持任何 OpenAI 兼容的 API 服务，包括但不限于：
- OpenAI (GPT-4, GPT-3.5等)
- 阿里云通义千问 (Qwen)
- 其他兼容 OpenAI API 格式的服务商

### API 端点示例
- **OpenAI**: `https://api.openai.com/v1/chat/completions`
- **阿里云百炼平台**: `https://dashscope.aliyuncs.com/compatible-mode/v1/chat/completions`
- **其他服务商**: 请参考对应服务商的 API 文档

## 2. 获取 API Key

### OpenAI
1. 访问 [OpenAI Platform](https://platform.openai.com/)
2. 注册并登录账户
3. 前往 API Keys 页面创建新的 API Key
4. 复制 API Key 并填写在 AronAI 的 `API Key` 输入框

### 阿里云百炼平台
1. 前往 [阿里云百炼控制台](https://bailian.console.aliyun.com/) 并登录
2. 跟随网页提示领取阿里云新用户的每个模型100万免费Tokens
3. 前往模型->密钥管理或直接访问 [密钥管理](https://bailian.console.aliyun.com/?tab=model#/api-key)
4. 创建 `API_KEY` 并记下，填写在 AronAI 的 `API Key` 输入框

## 3. 选择模型
根据您选择的 API 服务商，填写对应的模型名称：

### OpenAI 模型示例
- `gpt-4` - GPT-4 模型
- `gpt-4-turbo` - GPT-4 Turbo 模型
- `gpt-3.5-turbo` - GPT-3.5 Turbo 模型

### 阿里云通义千问模型示例
- `qwen-plus` - 通义千问 Plus 版本
- `qwen-turbo` - 通义千问 Turbo 版本
- `qwen-max` - 通义千问 Max 版本

## 4. 自定义 System Prompt（可选）
`System Prompt` 是选填项，默认值为 `You are a high-efficiency ai helper.`

您可以理解 System Prompt 为给 AI 的人设或角色定位。以下是一些示例：

### 专业助手
```
You are a professional assistant with expertise in technology, programming, and problem-solving. Provide accurate, detailed, and helpful responses.
```

### 创意写作助手
```
You are a creative writing assistant. Help users with storytelling, character development, and creative ideas. Be imaginative and inspiring.
```

### 代码专家
```
You are an expert programmer proficient in multiple programming languages. Provide clean, efficient code solutions with clear explanations.
```

## 5. 开始使用
1. 填写完所有必需字段（API 端点、模型名称、API Key）
2. 可选填写 System Prompt
3. 在底部输入框输入您的问题
4. 点击 `Send` 按钮或按 Enter 键发送消息
5. 使用 `Clear` 按钮可以清空对话历史

## 注意事项
- 请确保 API Key 的安全性，不要分享给他人
- 不同的模型有不同的定价和性能特点，请根据需求选择
- 某些 API 服务可能需要付费或有使用限制
- 确保 API 端点 URL 格式正确，必须是完整的 HTTPS URL