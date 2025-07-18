<div align="center">
<h1>CozeLoop 社区版</h1>
<p><strong> AI Agent 开发与运维的平台级解决方案</strong></p>
<p>
  <a href="#CozeLoop 能做什么？">CozeLoop </a> •
  <a href="#功能清单">功能清单</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#开发指南">开发指南</a>
</p>
<p>
  <img alt="License" src="https://img.shields.io/badge/license-apache2.0-blue.svg">
  <img alt="Go Version" src="https://img.shields.io/badge/go-%3E%3D%201.23.4-blue">
</p>

[English](README.md) | 中文

</div>

## 什么是 CozeLoop 

[CozeLoop ](https://www.coze.cn/loop) (CozeLoop) 是一个面向开发者，专注于 AI Agent 开发与运维的平台级解决方案。 它可以解决 AI Agent 开发过程中面临的各种挑战，提供从开发、调试、评估、到监控的全生命周期管理能力。

CozeLoop 在商业化版本的基础上，推出社区版免费对开发者开放核心基础功能模块，以开源模式共享核心技术框架，开发者可根据业务需求定制与扩展，便于社区共建、分享交流，助力开发者零门槛参与 AI Agent 的探索与实践。

## CozeLoop 能做什么？
CozeLoop 通过提供全生命周期的管理能力，帮助开发者更高效地开发和运维 AI Agent。无论是提示词工程、AI Agent 评测，还是上线后的监控与调优，CozeLoop 都提供了强大的工具和智能化的支持，极大地简化了 AI Agent 的开发流程，提升了 AI Agent 的运行效果和稳定性。

* **Prompt 开发**：CozeLoop 的 Prompt 开发模块为开发者提供了从编写、调试、优化到版本管理的全流程支持，通过可视化 Playground 实现 Prompt 的实时交互测试，让开发者能够直观比较不同大语言模型的输出效果。
* **评测**：CozeLoop 评测模块为开发者提供系统化的评测能力，能够对 Prompt 和扣子智能体的输出效果进行多维度自动化检测，例如准确性、简洁性和合规性等。
* **观测**：CozeLoop 为开发者提供了全链路执行过程的可视化观测能力，完整记录从用户输入到 AI 输出的每个处理环节，包括 Prompt 解析、模型调用和工具执行等关键节点，并自动捕获中间结果和异常状态。

## 功能清单
<table>
  <tr>
    <th>功能</th>
    <th>功能点</th>
    <th>商业版</th>
    <th>社区版</th>
  </tr>
  <tr>
    <td rowspan="2">Prompt 调试</td>
    <td>Playground 调试、对比、版本管理</td>
    <td>✔️</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Prompt 优化</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
  <tr>
    <td rowspan="3">评测</td>
    <td>评测集</td>
    <td>✔️</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>评估器</td>
    <td>✔️</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>实验</td>
    <td>✔️</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td rowspan="3">观测</td>
    <td>Trace</td>
    <td>✔️</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>指标</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
  <tr>
    <td>自动化任务</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
  <tr>
    <td rowspan="1">模型</td>
    <td>模型管理</td>
    <td>✔️</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td rowspan="2">安全</td>
    <td>SSO 登录</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
  <tr>
    <td>数据安全（VPC 私网链接、内容安全策略）</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
  <tr>
    <td rowspan="3">团队与企业管理</td>
    <td>工作空间与成员管理</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
  <tr>
    <td>多人协作</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
  <tr>
    <td>企业团队与权限</td>
    <td>✔️</td>
    <td>-</td>
  </tr>
</table>
## 快速开始
参考[快速开始](2.-快速开始)，了解如何安装部署 CozeLoop 最新版本。
## 使用 CozeLoop 社区版

* [Prompt 开发与调试](https://loop.coze.cn/open/docs/cozeloop/create-prompt)：CozeLoop 提供了完整的提示词开发流程。
* [评测](https://loop.coze.cn/open/docs/cozeloop/create-prompt)：CozeLoop 的评测功能提供标准评测数据管理、自动化评估引擎和综合的实验结果统计。
* [Trace 上报与查询](https://loop.coze.cn/open/docs/cozeloop/trace-integrate)：CozeLoop 支持对平台上创建的 Prompt 调试的 Trace 自动上报，实时追踪每一条 Trace 数据。
* [社区版使用CozeLoop  SDK](8.-社区版使用扣子罗盘-SDK)：CozeLoop 三个语言的 [SDK](https://loop.coze.cn/open/docs/cozeloop/sdk) 均适用于商业版和社区版。对于社区版，开发者只需要初始化时修改部分参数配置。

## 开发指南

* [系统架构](3.-系统架构)：了解CozeLoop 社区版的技术架构与核心组件。
* [启动模式](4.-服务启动模式)：安装部署CozeLoop 社区版时，默认使用开发模式，此模式下修改后端文件无需重新部署服务。
* [模型配置](5.-模型配置)：CozeLoop 社区版通过 Eino 框架支持多种 LLM 模型，参考此文档查看支持的模型列表，了解如何配置模型。
* [代码开发与测试](6.-代码开发与测试)：了解如何基于CozeLoop 社区版进行二次开发与测试。
* [故障排查](7.-故障排查)：了解如何查看容器状态、系统日志。

## License
本项目采用 Apache 2.0 许可证。详情请参阅 [LICENSE](https://code.byted.org/flowdevops/cozeloop/blob/feat/release/LICENSE) 文件。
## 社区贡献
我们欢迎社区贡献，贡献指南参见 [CONTRIBUTING](https://code.byted.org/flowdevops/cozeloop/blob/feat/release/CONTRIBUTING.md) 和 [Code of conduct](https://code.byted.org/flowdevops/cozeloop/tree/feat/release/CODE_OF_CONDUCT.md)，期待您的贡献！
## 安全与隐私
如果你在该项目中发现潜在的安全问题，或你认为可能发现了安全问题，请通过我们的[安全中心](https://security.bytedance.com/src) 或[漏洞报告邮箱](https://code.byted.org/flowdevops/cozeloop/blob/feat/release/sec@bytedance.com)通知字节跳动安全团队。
请**不要**创建公开的 GitHub Issue。
## 加入社区
飞书移动端扫描以下二维码，加入CozeLoop 技术交流群。

![Image](https://p9-arcosite.byteimg.com/tos-cn-i-goo7wpa0wc/d67b3c814a4742a58b127ed311eb84af~tplv-goo7wpa0wc-image.image)


## 致谢
感谢所有为 Cozeloop 项目做出贡献的开发者和社区成员。特别感谢：

* Eino 框架团队提供的 LLM 集成支持
* Cloudwego 团队开发的高性能框架
* 所有参与测试和反馈的用户
