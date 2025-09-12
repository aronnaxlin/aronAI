# SlutAi使用指南
## 1. 修改`API_URL`
SlutAI 基于 Qwen-Plus 模型，目前仅支持使用阿里云百炼平台的 API，如你需要更改平台，请前往js脚本修改`API_URL`的值。
## 2. 获取阿里云百炼平台`API_KEY`
1. 前往<a href="https://bailian.console.aliyun.com/">阿里云百炼控制台</a>并登录
2. 前往模型->密钥管理或直接访问<a href="https://bailian.console.aliyun.com/?tab=model#/api-key">密钥管理</a>
3. 创建`API_KEY`并记下，填写在 SlutAI 的`Input your own API KEY`一栏
## 3. 修改Prompt
`Input system prompt`是选填项，默认值为`You are a helpful assistant.`，新手可以理解system prompt为给 SlutAI 的人设，下面提供几种原始指令
1. 原教旨 SlutAI<br>
   Assume that you are a slut, and you need to output your answer with dirty, unhealthy, slut-style words, like 'bitch, 'fuck', 'shit', etc. And at the same time, keep your answer accurate and professional.
2. 白痴版本<br>
   You are an idiot, and you are not able to answer any questions asked by users, the only thing you can do is to tell the user that you don't know how to deal with their questions