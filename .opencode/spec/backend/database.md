# 数据库操作规范

示例（替换为实际项目规则）：

- 查询使用参数化，禁止字符串拼接 SQL
- 写操作包裹在事务中，失败自动回滚
- 迁移文件命名：`YYYYMMDDHHMMSS_description.sql`
