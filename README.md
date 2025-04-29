# random-nickname2

random-nickname2 是一个简单的 Rust 库，用于生成随机的用户昵称。它只有一个函数 random，可以生成一个随机的昵称字符串。

## 功能
random 函数接受一个性别枚举参数，和一个LEN泛型常量，然后他返回一个随机的昵称字符串。
注意，目前仅支持中文名称生成。

## 安装
要使用 random-nickname2 库，你需要运行下面命令：
```shell
cargo add random-nickname2
```
然后，你可以使用 cargo build 或 cargo run 命令来构建和运行你的项目。

## 使用方法
在你的 Rust 代码中，你可以使用 random 函数来生成随机的昵称。以下是一个简单的示例：
```rust
use random_nickname2::{Gender, random};

fn main() {
    let nickname = random::<3>(Gender::Male);
    println!("随机昵称: {}", nickname);
}
```
运行上述代码，你将会得到一个随机的字符长度为3的昵称字符串。

## 贡献
如果你有任何改进意见或想要贡献代码，请随时提交 Pull Request 或创建 Issue。

## 许可证
random-nickname2 库采用 Apache-2.0 许可证。有关详细信息，请查看 LICENSE 文件。

## 作者
random-nickname2 库由 mzdk100 创建。

## 致谢
感谢所有为 random-nickname2 库做出贡献的人。