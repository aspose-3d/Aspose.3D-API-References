---
title: "NodeVisitor"
second_title: "Aspose.3D for Java API 参考"
description: "回调函数，用于遍历整个节点层次结构。"
type: docs
weight: 261
url: /zh/java/com.aspose.threed/nodevisitor/
---
```
public interface NodeVisitor
```

回调函数，用于遍历整个节点层次结构。
## 方法

| 方法 | 描述 |
| --- | --- |
| [call(Node node)](#call-com.aspose.threed.Node-) | 回调函数，用于遍历整个节点层次结构。 |
### call(Node node) {#call-com.aspose.threed.Node-}
```
public abstract boolean call(Node node)
```


回调函数，用于遍历整个节点层次结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 正在访问的节点 |

**Returns:**
boolean - 返回 false 以停止遍历
