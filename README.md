# ChatGPT-API

基于[OpenAI GPT-3.5 Turbo API](https://platform.openai.com/docs/guides/chat)的演示。

自建 API 地址：https://chatgpt.qingyi1220.cn/

1. 配置环境和安装项目依赖

   > 首先，您需要安装[Node.js。](https://nodejs.org/) （需要 node 版本 18+）

   ```shell
   npm i
   ```

2. 制作一个副本`.env.example`，然后将其重命名为`.env`
3. 将您的[OpenAI API 密钥](https://platform.openai.com/account/api-keys)添加到`.env`
   ```
   OPENAI_API_KEY=sk-xxx...
   ```
4. 运行
   ```shell
   npm run dev
   ```

## Deploy With Vercel（推荐）

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/TsingYi1263/ChatGPT&env=OPENAI_API_KEY&envDescription=OpenAI%20API%20Key&envLink=https://platform.openai.com/account/api-keys)

用 Vercel 部署，Fork 到自己的仓库，填写自己的 OpenAI API Key 后部署即可。

> 准备事项：梯子(获取ChatGPT Key)、OpenAI 、vercel 、 GitHub账号、vercel 绑定 GitHub
