# nimble-jacket-tool

Software engineer @Slack

留着备查的示例

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 安装

```bash
git clone https://github.com/USER/nimble-jacket-tool.git
cd nimble-jacket-tool
cargo build --release
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## License

MIT
