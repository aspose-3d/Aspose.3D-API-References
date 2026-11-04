---
title: "Класс VertexDeclaration"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Utilities.VertexDeclaration. Объявление пользовательской структуры вершин"
type: docs
weight: 2910
url: /ru/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

Объявление структуры пользовательской вершины.

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | Получает количество всех полей, определённых в этом `VertexDeclaration` |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | Объект `VertexDeclaration` будет запечатлён, когда он будет использован [`TriMesh`](../../aspose.threed.entities/trimesh-1/) или [`TriMesh`](../../aspose.threed.entities/trimesh/), дальнейшие изменения не допускаются. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | Размер в байтах структуры вершины. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | Создайте `VertexDeclaration` на основе разметки [`Geometry`](../../aspose.threed.entities/geometry/). |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | Добавить новое поле вершины |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | Очистить все поля. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | Сравнивает этот экземпляр с указанным объектом и возвращает указание их относительных значений. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом `VertexDeclaration`, одинаковое значение. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | Получает перечислитель для обхода всех полей вершин в этом экземпляре. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | Возвращает хеш‑код для этой строки. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | Строковое представление `VertexDeclaration` |

### См. также

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


