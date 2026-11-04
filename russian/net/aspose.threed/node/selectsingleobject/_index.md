---
title: "Node.SelectSingleObject"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Выбирает один объект под текущим узлом, используя синтаксис запросов XPathlike."
type: docs
weight: 240
url: /ru/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

Выбрать один объект под текущим узлом, используя синтаксис запросов, похожий на XPath.

```csharp
public object SelectSingleObject(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Запрос XPath-like |

### Возвращаемое значение

Объект, найденный запросом XPath-like.

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
//Выберите один объект камеры под дочерними узлами узла с именем 'c' в корневом узле.
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// Выберите узел с именем 'a1' в корневом узле, даже если 'a1' не является прямым дочерним узлом.
var obj = s.RootNode.SelectSingleObject("a1");
//Выберите сам узел, так как '/' выбирается непосредственно в корневом узле, поэтому выбирается корневой узел.
obj = s.RootNode.SelectSingleObject("/");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


