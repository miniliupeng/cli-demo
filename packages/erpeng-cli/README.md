# 1、yargs 解析命令参数
```
// yargs.argv.name
erpeng --name=orderPage
erpeng --name orderPage
```
# 2、inquirer 用户交互

# 3、copy-dir 拷贝文件夹模块

# 4、拷贝文件模块 fs.readFileSync fs.writeFileSync

# 5、mustache 动态文件内容

# 6、child_process 自动安装依赖模块 
child_process.exec(command, options, callback)

command：命令，比如 pnpm install
options：参数

cwd：设置命令运行环境的路径
env：环境变量
timeout：运行执行现在


callback：运行命令结束回调，(error, stdout, stderr) =>{ }，执行成功后 error 为 null，执行失败后 error 为 Error 实例，stdout、stderr 为标准输出、标准错误，其格式默认是字符串。

# 7、 ora 加载动画