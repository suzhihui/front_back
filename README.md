# 设计数据库结构

- sequlize 库
    - sequlize: 供程序使用
    - sequlize-cli: 供命令行使用的工具

##### 初始化
> sequlize init
初始化以后会生成

- config: 配置目录
- migrations: 迁移文件（数据库表结构）
- seeders: 种子文件 （生成测试数据）
- models: 模型文件 （sequlize 命令工具使用不多，主要是给程序使用）

##### 创建数据库
> sequelize db:create

##### 构建数据迁移结构
> sequelize migration:create --name [迁移文件的名称]

##### 数据结构
- user: 用户表
- user-prefile: 用户扩展信息表