# 安装rust环境
运行如下命令：
```shell
curl https://sh.rustup.rs -sSf | sh
```
## 配置环境变量
配置 PATH 环境变量
在 Rust 开发环境中，所有工具都安装到 ~/.cargo/bin 目录， 并且您能够在这里找到 Rust 工具链，包括 rustc、cargo 及 rustup。  
因此，Rust 开发者们通常会将此目录放入 PATH 环境变量。在安装时，rustup 会尝试配置 PATH， 但是因为不同平台、命令行之间的差异，以及 rustup 的 bug，对于 PATH 的修改将会在重启终端、用户登出之后生效，或者有可能完全不会生效。  
当安装完成之后，如果在控制台运行 `rustc --version` 失败，这是最可能的原因。  
## 测试安装结果  
运行`rustc --version`，如果安装成功就会看到rust版本号。
