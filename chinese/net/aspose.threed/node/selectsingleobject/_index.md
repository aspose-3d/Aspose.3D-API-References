---
title: "Node.SelectSingleObject"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。使用类似 XPath 的查询语法在当前节点下选择单个对象"
type: docs
weight: 240
url: /zh/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

使用类似 XPath 的查询语法选择当前节点下的单个对象。

```csharp
public object SelectSingleObject(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 类似 XPath 的查询 |

### 返回值

对象通过类似 XPath 的查询定位。

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
//在根节点下名为 'c' 的节点的子节点中选择单个相机对象
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// 在根节点下选择名为 'a1' 的节点，即使 'a1' 不是直接子节点
var obj = s.RootNode.SelectSingleObject("a1");
//选择节点本身，因为 '/' 直接在根节点上选择，所以根节点被选中。
obj = s.RootNode.SelectSingleObject("/");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


