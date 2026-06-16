---
title: "Node.SelectObjects"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。使用类似 XPath 的查询语法选择当前节点下的多个对象"
type: docs
weight: 230
url: /zh/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

使用类似 XPath 的查询语法选择当前节点下的多个对象。

```csharp
public List<object> SelectObjects(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 类似 XPath 的查询 |

### 返回值

多个对象匹配 XPath‑like 查询。

### 异常

| 异常 | 条件 |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | 如果路径包含格式错误的查询，将抛出 ParseException。 |

## 示例

使用类似 XPath 的表达式选择单个节点

```csharp
//创建用于测试的场景
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//选择类型为 Camera 或名称为 'light' 的对象，无论它们位于何处。
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


