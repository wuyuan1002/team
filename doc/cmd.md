
1. cargo test --workspace: 执行所有workspace的单测
2. cargo test -p {package-name}: 执行指定package的单测
3. cargo run --example {example-name}: 执行指定的example
4. cargo run --bin {binary-name}: 编译并运行指定的binary
5. cargo check: 进行语法检查
6. cargo build: 编译项目

7. cargo login {crates.io token}: 登录[crates.io](https://crates.io/)
8. cargo publish: 上传当前目录Cargo.toml文件所描述的package
