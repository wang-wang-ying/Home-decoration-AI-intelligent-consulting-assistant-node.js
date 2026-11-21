# Home-decoration-AI-intelligent-consulting-assistant-node.js
# 家居装修AI智能体咨询助手-node.js
### 1、核心功能
家居装修智能咨询助手以AI智能体为核心，专注于家居领域的智能问答服务,开发者可通过该平台学习如何将AI智能体与Node.js后端技术（Express、Prisma、Zod）深度融合，实现家居装修领域的专属智能对话功能!

- 智能体配置：定义家居装修智能体的名称、问候语、系统提示词和启停状态，支持Markdown编辑与分屏预览

- 智能体对话：基于大模型的SSE流式对话，支持多轮上下文、会话管理与历史记录，实现家居装修智能体与用户的实时交互

- 大模型配置：为智能体提供大模型底座，维护接口地址、API Key和模型名称，支持掩码安全展示

- 用户管理：前台注册用户的分页查询、搜索筛选与详情查看

- 聊天记录管理：管理员可追溯所有用户与家居装修智能体的对话记录，支持分页、搜索与详情查看

- 登录与注册：管理员与普通用户统一登录入口，MD5加盐加密，JWT令牌鉴权

注：

平台内置大模型使用的是DeepSeek，需要自行去官网开通。

家居装修智能体的回答结果仅作参考，不保证回答内容的准确性与专业性。

智能体仅回答家居装修相关问题，超出装修领域的问题将不予解答。

<img width="1891" height="926" alt="3-首页" src="https://github.com/user-attachments/assets/47f161ee-73e4-41fe-94d4-bb9ee4cf1e00" />


### 2、涉及到技术知识点

通过搭建家居装修智能体咨询服务，开发者可以掌握以下核心知识：

- 智能体构建：学习如何通过系统提示词（System Prompt）定义家居装修智能体的角色定位、能力边界和回答风格，限定智能体仅回答装修相关问题

- SSE流式响应：学习如何使用Express的流式响应（Response Stream）实现智能体对话的逐字推送，打造打字机效果的实时交互体验

- 敏感信息掩码：学习API Key等敏感凭证的安全处理策略，防止信息泄露

- Markdown编辑与预览：学习前端Markdown实时渲染与分屏滚动同步的实现技巧

- Zod数据校验：学习使用Zod模型定义请求参数与响应数据的校验规则和序列化方式

- Express中间件机制：学习Express的中间件机制，实现数据库会话管理和鉴权逻辑的优雅复用

### 3、技术栈及部署搭建使用
后端：Node.js + Express

前端：Vue3 + Element Plus

数据库：MySQL 8.0

部署时只需配置好MySQL数据库、大模型API地址与密钥，并确保后端服务与前端的接口对接顺畅，系统即可运行

### 4、源码
演示站及获取👉https://www.wwwoop.com/home/projectInfo?goodsId=208&typeParam=&subKey=-1

项目配套文档（免费领取）👉https://www.wwwoop.com/home/documentDetail?bookstoreId=109

<img width="1458" height="2054" alt="1" src="https://github.com/user-attachments/assets/e0e47680-cfe8-4dba-a9de-0b06de9f79a3" />



