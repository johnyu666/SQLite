# SQLite

## 新建库
` # sqlite2 test.db `
## 查看库
`sqlite> .database`
## 查看表
`sqlite>.tables`
## 查看表结构
`sqlite>.schema tablename`
## 退出
`sqlite> .quit`
## 以sql方式导出数据库
`# sqlite3 john.db .dump > john.sql`
## 使用sql恢复数据库
`# sqlite3 john1.db<john.sql`
## 查询显示列名称
`sqlite>.header on`
## 格式化查询（列对齐）
`sqlite>.mode column`
