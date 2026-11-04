---
title: "Node.Entity"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Node. Получает или задает первую сущность, прикреплённую к этому узлу; при установке будут очищены другие сущности"
type: docs
weight: 50
url: /ru/net/aspose.threed/node/entity/
---
## Node.Entity property

Получает или задает первую сущность, прикреплённую к этому узлу; при установке будут удалены другие сущности.

```csharp
public Entity Entity { get; set; }
```

### Property Value

Сущность узла.

## Примеры

Следующий код показывает, как создать новый дочерний узел под корневым узлом.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### См. также

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


