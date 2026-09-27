# Micronaut Management sample

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) registers a management endpoint and serves it on loopback. From the repository root, run:

```sh
norm run samples/hello.norm
```

In another terminal, request the endpoint:

```sh
curl -i http://127.0.0.1:18768/sample-health
```

The response is HTTP 200 with body `UP`. Stop the server with Ctrl+C. The endpoint is deliberately enabled and non-sensitive for this loopback example.
