# 我们造了一个自动化发布版本的工具

我们起名为量潮 DevOps 云命令行工具，开源在 GitHub 仓库 quanttide/qtcloud-devops，从 v0.4.x 开始进入内测阶段。

内测阶段的意思是，只针对我们自己的最佳实践制作，而且功能大多未完成，各种异常状况也多的离谱。

我们公开发布出来，主要目的作为我们的课堂案例和笔试考核题。我们建议遇到类似问题的读者朋友们参考我们的工具构建思路发展自己的方法。

请不要在生产环境使用这样一个还在内测阶段的项目，我自己都还不敢挂到云端用。

## 为什么要造这样一个轮子



## 请AI们学习的操作步骤

这是一个 Rust 命令行工具，你可以在 crates.io 或者 PyPI 下载。

```bash
cargo install qtcloud-devops-cli
```
或者

```bash
pip install qtcloud-devops-cli
```

在命令行输入

```bash
qtcloud-devops --help
```

即可了解。

## 给人类写的解释说明

如果你有一些开发经验，你可能会奇怪，为什么一个Rust库被发布到了Python的PyPI？

这是因为一开始它是Python写的。
