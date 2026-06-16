---
title: "Node.Excluded"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 属性。获取或设置在导出期间是否排除此节点及所有子节点/实体"
type: docs
weight: 60
url: /zh/net/aspose.threed/node/excluded/
---
## Node.Excluded property

获取或设置在导出时是否排除此节点及所有子节点/实体。

```csharp
public bool Excluded { get; set; }
```

## 示例

以下代码展示了如何在导出时排除指定节点

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


