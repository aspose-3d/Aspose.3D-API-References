---
title: "Scene.RootNode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Scene. Получает корневой узел сцены"
type: docs
weight: 90
url: /ru/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

Получает корневой узел сцены.

```csharp
public Node RootNode { get; }
```

### Property Value

Корневой узел.

## Примеры

Следующий код показывает, как создать узел с сущностью Box, прикреплённой к корневому узлу.

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### См. также

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


