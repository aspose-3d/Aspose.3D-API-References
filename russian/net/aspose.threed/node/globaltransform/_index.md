---
title: "Node.GlobalTransform"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Node. Возвращает глобальное преобразование"
type: docs
weight: 70
url: /ru/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

Получает глобальное преобразование.

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

Глобальное преобразование.

## Примеры

Следующий код показывает, как прочитать глобальное преобразование узла

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//разместите коробку в (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### См. также

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


