# org.json 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) —— 解析事件、更新访问次数，并读取可选字段。这是通过自身的 `Module module()` 声明依赖的独立消费者程序。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

[module.norm](../org/json/module.norm) 指定 Java 制品版本并定义公开 API。

预期输出：

```text
Norm
3
new
```

API 入口：[module.norm](../org/json/module.norm) 列出公开的 `JSONObject`。[适配器验收示例](../examples/sample/org/json/Main.norm)覆盖更多绑定行为。
