---
title: "Node.SelectObjects"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Выбирает несколько объектов под текущим узлом, используя синтаксис запросов, похожий на XPath."
type: docs
weight: 230
url: /ru/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

Выбрать несколько объектов под текущим узлом, используя синтаксис запросов, похожий на XPath.

```csharp
public List<object> SelectObjects(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Запрос XPath-like |

### Возвращаемое значение

Несколько объектов соответствуют XPath-подобному запросу.

### Исключения

| исключение | условие |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | Будет выброшено исключение ParseException, если путь содержит некорректный запрос. |

## Примеры

Выберите один узел, используя выражение XPath-like.

```csharp
//Создайте сцену для тестирования.
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//Выбрать объекты, у которых тип Camera или имя 'light', независимо от их расположения.
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


