# RequestJson class

一个类，表示 `HTTP POST` 请求的 `JSON` 结构。

```csharp
public sealed class RequestJson
```

## Public Members

| name | description |
| --- | --- |
| [RequestJson](RequestJson/RequestJson.md)() | The default constructor. |
| [senderNick](RequestJson/senderNick.md) { get; set; } | 发送消息的用户昵称。 |
| [text](RequestJson/text.md) { get; set; } | 获取一个值，存储着用户发送的消息文本。 |

## Remarks

当用户 `@` 目标机器人时，钉钉服务器会向开发者设置的服务器发送 `HTTP POST` 请求, 其 `BODY` 是一个 `JSON` 结构。

次类就是 `JSON` 结构的简化版，只要求最关键的信息。

钉钉开发文档中为此结构定义了更多的字段：

https://ding-doc.dingtalk.com/doc?spm=a2115p.8777639.0.0.205a4260i2g1Q8#/serverapi2/elzz1p

## See Also

* namespace [DingDingDiceBot](../DingDingDiceBot.md)

<!-- DO NOT EDIT: generated by xmldocmd for DingDingDiceBot.dll -->
