---
title: "Node.Merge"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Отсоединяет всё под узлом и присоединяет к текущему узлу"
type: docs
weight: 220
url: /ru/net/aspose.threed/node/merge/
---
## Node.Merge method

Отсоединить всё под узлом и прикрепить к текущему узлу.

```csharp
public void Merge(Node node)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | Узел |  |

## Примеры

Следующий код показывает, как объединить два 3D‑файла в один файл

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


