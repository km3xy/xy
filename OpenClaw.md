OpenClaw 是一款MIT开源、本地优先的跨平台 AI 智能体（Agent），核心定位是“能在设备上实际完成任务的个人助理”，由 Peter Steinberger 主导开发，前身为 Clawdbot/Moltbot。
 
 
 
核心要点
 
- 定位：自托管的 AI 执行中枢，连接大语言模型、通讯渠道与系统工具，实现自然语言驱动的本地自动化。
​
- 核心设计：本地优先、数据自主可控；配置与记忆以 Markdown 本地存储，支持可视化编辑与对话式调整 。
​
- 能力范围：系统操控（文件、终端、键鼠、浏览器）、跨平台消息交互（微信、企业微信、钉钉、飞书、Telegram、Discord 等）、工作流自动化与插件扩展。
​
- 模型兼容：支持 OpenAI、Claude、Gemini 等云端模型，也适配 Ollama、LocalAI 等本地私有化部署。
​
- 部署方式：本地自托管（Windows/macOS/Linux）、Docker/虚拟机隔离，以及阿里云、腾讯云等一键云端部署 。
 
快速上手（最简）
 
1. 准备：Node.js ≥22、AI 模型 API Key（或本地模型服务）。
​
2. 安装： npm install -g openclaw 。
​
3. 初始化： openclaw onboard ，按向导配置模型与通讯渠道（如微信扫码登录）。
​
4. 验证：发送  /status  查看状态，或指令“帮我写一封邮件”测试执行。
 
安全提示
 
- 版本≥2026.1.29，保持认证开启，优先在 Docker/虚拟机中运行，降低权限风险。
​
- 警惕恶意插件，优先从官方 Clawhub 安装技能，定期更新与审计配置。
 
资源与标识
 
- 官方仓库：github.com/openclaw/openclaw（TypeScript，MIT 协议） 。
​
- 官方网站：openclaw.ai 。
​
- 社区生态：Clawhub（技能市场）、Lobster（工作流引擎） 。
 
 
 
⚠️ 注意：另有同名OpenCLAW是求解双曲型偏微分方程的 Python 数值模拟框架，与本 AI 智能体为不同项目，避免混淆。
