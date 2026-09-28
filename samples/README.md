# org.json samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Parse an event, update its visit count, and read an optional field. This is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

[module.norm](../org/json/module.norm) pins the Java artifact and defines the public API.

Expected output:

```text
Norm
3
new
```

API reference: [module.norm](../org/json/module.norm) lists the exposed `JSONObject`. The [adapter acceptance example](../examples/sample/org/json/Main.norm) exercises additional binding behavior.
