---
title: "Node.AddChildNode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Добавляет дочерний узел к этому узлу"
type: docs
weight: 150
url: /ru/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

Добавить дочерний узел к этому узлу

```csharp
public void AddChildNode(Node node)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | Узел | Дочерний узел, который будет присоединён |

## Примеры

Следующий код показывает, как получить все сетки из сцены

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//добавьте новый узел вручную
scene.RootNode.AddChildNode(newNode);
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


