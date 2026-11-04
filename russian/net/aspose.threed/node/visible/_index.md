---
title: "Node.Visible"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Node. Получает или задает, показывать ли узел"
type: docs
weight: 130
url: /ru/net/aspose.threed/node/visible/
---
## Node.Visible property

Получает или задает отображение узла

```csharp
public bool Visible { get; set; }
```

## Примеры

Следующий код показывает, как создать невидимый узел

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


