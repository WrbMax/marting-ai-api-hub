# 🚀 Marting AI API Hub

<p align="center">
  <b>一站式 AI 模型 API 聚合分发平台，开发者的高性价比首选！</b>b>
</p>p>

<p align="center">
  <a href="https://marting.pro">🌐 访问官网 (marting.pro)</a>a> •
    <a href="https://marting.pro/doc">📚 API 接入文档</a>a> •
      <a href="https://marting.pro/pricing">💰 极简定价</a>a>
</p>p>

## ✨ 为什么选择 Marting AI？

在 AI 爆发的时代，开发者往往需要同时接入 OpenAI、Anthropic、Google 等多家的模型，繁琐的注册、绑卡、网络连通问题让人头疼。**Marting AI API Hub** 为此而生：

- **🔥 极致全面**：单 API 接口支持 GPT-4.5、Claude 3.5、Gemini 1.5 Pro 等近 **600种** 主流大模型！
- - **⚡️ 高并发低延迟**：企业级线路优化，保障业务稳定运行。
  - - **💰 超高性价比**：拒绝高昂溢价，多种计费模式任你选。
    - - **🛠️ 无缝平替**：完全兼容 OpenAI 接口格式，只需修改 `Base URL` 和 `API Key`，一行代码完成接入！
      -
      - ## 🚀 快速开始
      -
      - 只需 1 分钟，即可将 Marting AI 接入您的项目。
      -
      - ### 1. 获取 API Key
      - 前往 [Marting.pro](https://marting.pro) 注册账号，在后台获取您的专属 API Key。
      -
      - ### 2. 代码接入示例
      -
      - 完全兼容 OpenAI 官方 SDK。
      -
      - #### Python (OpenAI SDK)
      -
      - ```python
        import os
        from openai import OpenAI

        client = OpenAI(
            api_key="您的_API_KEY",
            base_url="https://api.marting.pro/v1" # 替换为我们的 Base URL
        )

        response = client.chat.completions.create(
            model="gpt-4-turbo", # 或者 claude-3-opus-20240229 等近600种模型
            messages=[
                {"role": "system", "content": "你是一个得力的编程助手。"},
                {"role": "user", "content": "写一个 Python 的 Hello World。"}
            ]
        )

        print(response.choices[0].message.content)
        ```

        #### Node.js (OpenAI SDK)

        ```javascript
        import OpenAI from 'openai';

        const openai = new OpenAI({
          apiKey: '您的_API_KEY',
          baseURL: 'https://api.marting.pro/v1', // 替换为我们的 Base URL
        });

        async function main() {
          const chatCompletion = await openai.chat.completions.create({
            messages: [{ role: 'user', content: 'Say this is a test' }],
            model: 'gpt-4-turbo',
          });
          console.log(chatCompletion.choices[0].message.content);
        }

        main();
        ```

        ## 🧩 热门开源项目无缝接入

        Marting AI 完美支持各类热门开源 AI 客户端。

        ### LobeChat 接入配置
        - **OpenAI API Key**: 填入您的 Marting API Key
        - - **OpenAI 接口地址**: `https://api.marting.pro/v1`
          -
          - ### ChatGPT-Next-Web 接入配置
          - 在环境变量中设置：
          - ```bash
            OPENAI_API_KEY=您的_API_KEY
            BASE_URL=https://api.marting.pro
            ```

            ## 🎁 专属福利

            🎉 **新用户注册即享体验额度！**
            现在注册并使用，即可体验全网最全的模型矩阵。

            👉 **[立即注册获取 API Key](https://marting.pro)**

            ---
            *注：本项目为官方推广与开发者交流仓库，如有任何技术问题或合作意向，欢迎提交 Issue 或访问官网联系客服。*</b>
