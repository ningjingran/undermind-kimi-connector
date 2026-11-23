# Undermind Kimi 本地连接器

此仓库托管 Kimi Code 本地 Undermind 连接器所需的公开 Client ID Metadata Document（CIMD）。完整连接器以便携 ZIP 安装包交付。

- 用途：文献深搜、PDF 阅读、证据矩阵和带引用笔记，不生成论文正文。
- OAuth：authorization code + PKCE（S256）。
- 回调：`http://127.0.0.1:8799/callback`。
- 本机令牌：默认保存在 `~/.kimi-code/storages/undermind-mcp-auth.json`，权限 `0600`。
- 本仓库不保存任何访问令牌、刷新令牌或用户研究数据。

OAuth、令牌管理和 Streamable HTTP 客户端模块改编自 `VANuVANuu/dsh-plugin-undermind`（MIT），原版权声明保留在安装包的 `LICENSE` 中。
