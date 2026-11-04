---
title: "Node.Excluded"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Node. Получает или задает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте"
type: docs
weight: 60
url: /ru/net/aspose.threed/node/excluded/
---
## Node.Excluded property

Получает или задает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте.

```csharp
public bool Excluded { get; set; }
```

## Примеры

Следующий код показывает, как исключить указанный узел при экспорте

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


