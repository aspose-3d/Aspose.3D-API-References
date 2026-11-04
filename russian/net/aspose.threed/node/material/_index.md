---
title: "Node.Material"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Node. Получает или задает первый материал, связанный с этим узлом; при установке будут очищены другие материалы"
type: docs
weight: 80
url: /ru/net/aspose.threed/node/material/
---
## Node.Material property

Получает или задает первый материал, связанный с этим узлом; при установке будут удалены другие материалы

```csharp
public Material Material { get; set; }
```

### Property Value

Материал.

## Примеры

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### См. также

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


