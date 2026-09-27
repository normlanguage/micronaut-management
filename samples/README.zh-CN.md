# Micronaut Management 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) 注册管理端点并在本机回环地址提供服务。在仓库根目录运行：

```sh
norm run samples/hello.norm
```

在另一个终端请求端点：

```sh
curl -i http://127.0.0.1:18768/sample-health
```

响应状态为 HTTP 200，正文为 `UP`。按 Ctrl+C 停止服务。为了本机示例，该端点明确启用并设为非敏感。
