---
title: "Node.ChildNodes"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Node. Возвращает дочерние узлы"
type: docs
weight: 30
url: /ru/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

Получает дочерние узлы.

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

Узлы.

## Примеры

Следующий код показывает, как перечислить дочерний узел корневого узла

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //выполняйте свою работу
}
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


