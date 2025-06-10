使用前准备工作：
1. 修改`mcp.json`中的应用信息 <your_app_id>、<your_app_secret>，参考[飞书MCP文档](https://open.feishu.cn/document/uAjLw4CM/ukTMukTMukTM/mcp_integration/advanced-configuration)获取
2. 手动创建一个多维表格，并修改`system.md`中的多维表格唯一标识 {app_token}、{table_id}， 可参考 https://open.feishu.cn/document/server-docs/docs/bitable-v1/app-table-record/create 文档获取这两个参数
3. 修改`system.md`中消息发送参数 <bitable_url>、<feishu_chat_id>，<bitable_url>为多维表格的访问链接，<feishu_chat_id> 为飞书群ID（参考 https://open.feishu.cn/document/server-docs/group/chat/chat-id-description）