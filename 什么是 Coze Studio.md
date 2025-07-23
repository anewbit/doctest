## 什么是 Coze Studio
[Coze Studio](https://www.coze.cn/home) 是一站式 AI Agent 开发工具。提供各类最新大模型和工具、多种开发模式和框架，从开发到部署，为你提供最便捷的 AI Agent 开发环境。上万家企业、数百万开发者正在使 Coze Studio。

* **提供 AI Agent 开发所需的全部核心技术**：Prompt、RAG、Plugin、Workflow、UI Builder ，使得开发者可以聚焦创造 AI 核心价值。
* **开箱即用，用最低的成本开发最专业的 AI Agent：​**Coze Studio 为开发者提供了健全的应用模板和编排框架，你可以基于它们快速构建各种 AI Agent ，将创意变为现实。Coze Studio 支持集成火山引擎各类资源，方便你的 AI Agent 实现快速扩容。

Coze Studio 是字节跳动新一代 AI Agent 开发平台**扣子（Coze）**的**开源版本**。通过 Coze Studio 提供的可视化设计与编排工具，开发者可以通过零代码或低代码的方式，快速打造和调试智能体、应用和工作流，实现强大的 AI 应用开发和更多定制化业务逻辑，是构建面向非编程用户的低代码 AI 产品的理想选择。Coze Studio 致力于降低 AI Agent 开发与应用门槛，鼓励社区共建和分享交流，助你在 AI 领域进行更深层次的探索与实践。

Coze Studio 的后端采用 Golang 开发，前端使用 React + TypeScript，整体基于微服务架构并遵循领域驱动设计（DDD）原则构建。为开发者提供一个高性能、高扩展性、易于二次开发的底层框架，助力开发者应对复杂的业务需求。

## Coze Studio 能做什么

借助扣子提供的可视化设计与编排工具，你可以通过零代码或低代码的方式，快速搭建出基于大模型的各类 AI 项目，满足个性化需求、实现商业价值。

* **搭建智能体**：智能体是基于对话的 AI 项目，它通过对话方式接收用户的输入，由大模型自动调用插件或工作流等方式执行用户指定的业务流程，并生成最终的回复。智能客服、虚拟伴侣、个人助理、英语外教都是智能体的典型应用场景。
* **搭建 AI 应用**：应用是指利用大模型技术开发的应用程序。扣子中搭建的 AI 应用具备完整业务逻辑和可视化用户界面，是一个独立的 AI 项目。通过扣子开发的 AI 应用有明确的输入和输出，可以根据既定的业务逻辑和流程完成一系列简单或复杂的任务，例如 AI 搜索、翻译工具、饮食记录等。
* **搭建工作流**：扣子的工作流功能可以用来处理逻辑复杂，且有较高稳定性要求的任务流。扣子提供了大量灵活可组合的节点包括大语言模型 LLM、自定义代码、判断逻辑等，无论你是否有编程基础，都可以通过拖拉拽的方式快速搭建一个工作流。例如创建一个撰写行业研究报告的工作流，让智能体写一份 20 页的报告。

## 快速开始
参考[快速开始](https://github.com/coze-dev/coze-studio/wiki/2.-快速开始)，了解如何获取并部署 Coze Studio 社区版，快速构建项目、体验 Coze Studio 社区版。
## 功能清单
<table>
        <thead>
            <tr>
                <th>功能模块</th>
                <th>功能点</th>
                <th>商业版</th>
                <th>社区版</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="1">搭建智能体</td>
                <td>编排、发布、管理智能体</td>
                <td>✔️</td>
                <td>✔️</td>
            </tr>
            <tr>
                <td rowspan="1">搭建应用</td>
                <td>通过工作流搭建业务逻辑</td>
                <td>✔️</td>
                <td>✔️</td>
            </tr>
            <tr>
                <td rowspan="1">搭建工作流</td>
                <td>创建、修改、发布、管理工作流</td>
                <td>✔️</td>
                <td>✔️</td>
            </tr>
            <tr>
                <td rowspan="2">插件等开发资源</td>
                <td>插件、知识库、数据库、提示词</td>
                <td>✔️</td>
                <td>✔️</td>
            </tr>
            <tr>
                <td>音色、卡片、音视频通话等</td>
                <td>✔️</td>
                <td>-</td>
            </tr>
            <tr>
                <td rowspan="1">企业与团队空间</td>
                <td>企业团队管理、多人协作、SSO 等特性</td>
                <td>✔️</td>
                <td>-</td>
            </tr>
            <tr>
                <td rowspan="3">API 与 SDK</td>
                <td>OpenAPI</td>
                <td>✔️</td>
                <td>✔️</td>
            </tr>
            <tr>
                <td>Chat SDK</td>
                <td>✔️</td>
                <td>✔️</td>
            </tr>
            <tr>
                <td>Realtime 等 SDK、API</td>
                <td>✔️</td>
                <td>-</td>
            </tr>
        </tbody>
    </table>

