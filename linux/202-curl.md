# curl命令

#### 实例

* get请求

```shell
curl http://www.baidu.com
```

* post请求

```shell
curl -X POST \
  -H "Accept:application/json" \
  -H "Content-type:application/json" \
  -d '{"key":"value"}' \
  'http://www.test.com'
```

## 命令参数

```shell
-v   打印出请求和返回的详细内容（包含header）
-i --include 打印响应的详细信息
```

## 一些技巧

1. 在curl响应体的末尾自动添加换行符

在`~/.curlrc`中添加

```
-w '\n'
```
