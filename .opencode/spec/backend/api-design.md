# API 设计规范

示例（替换为实际项目规则）：

- RESTful 路径使用复数名词：`/api/users`、`/api/orders`
- 分页参数统一为 `page` + `pageSize`，默认 page=1, pageSize=20
- 错误响应使用统一格式：`{ "error": { "code": "...", "message": "..." } }`
