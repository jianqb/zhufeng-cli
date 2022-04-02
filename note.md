## 将包变成全局的
- 先创建可执行的脚本 #! /usr/bin/env node
- 配置package.json 中的 bin 字段
- npm link 链接到本地环境(默认以 name 为基准)

- bin 取值可以是对象，也可以是字符串

> link 相当于将本地模块链接到 npm 目录下，这个 npm 目录可以直接访问，所以当前包就可以直接访问了