# yew quick start

使用`yew`构建SPA

## Get Started

### 预下载
``` bash
$ cargo install wasm-pack          # 编译rust为wasm，并生成js胶水代码 （Windows需要使用官网安装程序）
$ cargo install cargo-make         # Task runner
$ cargo install simple-http-server # 简单服务器
```

### 启动

```bash
$ cargo make build # 自动检测rust代码变化自动编译为wasm
$ cargo make dev # 启动开发服务
```