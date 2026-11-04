---
title: "Node.Accept"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Проходит через все дочерние узлы, включая текущий узел, и вызывает посетителя с узлом. Посетитель может прервать обход, вернув false"
type: docs
weight: 140
url: /ru/net/aspose.threed/node/accept/
---
## Node.Accept method

Проходит по всем дочерним узлам (включая текущий узел) и вызывает посетителя с узлом. Посетитель может прервать обход, вернув false

```csharp
public bool Accept(NodeVisitor visitor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| посетитель | NodeVisitor | Обратный вызов Visitor для посещения узла |

### Возвращаемое значение

true означает, что посетитель прервал обход.

## Примеры

Следующий код показывает, как получить все сетки из сцены

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //продолжить поиск
    return true;
});
```

### См. также

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


