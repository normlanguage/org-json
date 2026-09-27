# org.json

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `org/json`. It pins org.json 20260814 and defines its package coordinates in [module.norm](org/json/module.norm). The public API covers common JSON objects and arrays, parsing, querying, modification, serialization, and iteration.

Standalone NAR consumption, JSON parsing and modification, Object boundaries, and ordinary Norm iteration are covered by `OrgJsonBindingIntegrationTest`. The complete API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.

[Runnable samples](samples/README.md) demonstrate the library as an external Norm dependency.
