# Xray Mai Bot V2 Pver

**建议您至少拥有一定的编程基础之后再尝试使用本工具。**

## 使用

Install：

```shell
poetry install
```

Update：

```shell
poetry update
```
Start

```shell
poetry run nb run
```

## 配置环境

> .env

```
HOST=127.0.0.1 #Onebot V11相关连接配置
PORT=11451
LOG_LEVEL=SUCCESS #日志输出等级
SUPERUSERS=[] #超级管理员用户
COMMAND_START=[""] #命令起始字符
```



## 运行配置项

> src/libraries/GLOBAL_CONSTANT.py

```
# Mongo服务器配置
MONGO_USERNAME = ''
MONGO_PASSWORD = ''
MONGO_HOST = '127.0.0.1'
MONGO_PORT = 27017
MONGO_DATABASE = 'admin' # 身份校验数据库
MONGO_DB = 'xray-mai-bot' # 连接数据库
```