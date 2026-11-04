---
title: "Node.Transform"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Node. Получает локальную трансформацию."
type: docs
weight: 120
url: /ru/net/aspose.threed/node/transform/
---
## Node.Transform property

Получает локальное преобразование.

```csharp
public Transform Transform { get; }
```

### Property Value

Трансформация.

## Примеры

Следующий код показывает, как изменить преобразование узла:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//разместите коробку в (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### См. также

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


