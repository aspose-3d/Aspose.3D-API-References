---
title: "Node.GetChild"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Возвращает дочерний узел по указанному индексу"
type: docs
weight: 200
url: /ru/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

Получает дочерний узел по указанному индексу.

```csharp
public Node GetChild(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | Int32 | Индекс. |

### Возвращаемое значение

Дочерний элемент.

## Примеры

Следующий код показывает, как получить дочерний узел по указанному индексу.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

Получает дочерний узел с указанным именем

```csharp
public Node GetChild(string nodeName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя дочернего узла для поиска. |

### Возвращаемое значение

Дочерний элемент.

## Примеры

Следующий код показывает, как получить дочерний узел с указанным именем.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


