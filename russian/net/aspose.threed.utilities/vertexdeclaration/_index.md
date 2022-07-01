---
title: VertexDeclaration
second_title: Справочник по Aspose.3D для .NET API
description: Объявление пользовательской структуры вершин
type: docs
weight: 2680
url: /ru/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

Объявление пользовательской структуры вершин

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VertexDeclaration](vertexdeclaration)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count) { get; } | Получает количество всех полей, определенных в этом[`VertexDeclaration`](../vertexdeclaration) |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed) { get; } | A[`VertexDeclaration`](../vertexdeclaration)будет запечатан, когда его использует[`TriMesh`](../../aspose.threed.entities/trimesh-1)или[`TriMesh`](../../aspose.threed.entities/trimesh), дальнейшие модификации не допускаются. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size) { get; } | Размер вершинной структуры в байтах. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry)(Geometry, bool) | Создать[`VertexDeclaration`](../vertexdeclaration)на основеМакетGeometry. |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield)(VertexFieldDataType, VertexFieldSemantic, int, string) | Добавить новое поле вершин |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear)() | Очистить все поля. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto)(VertexDeclaration) | Сравнивает этот экземпляр с указанным объектом и возвращает индикацию их относительных значений. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals)(object) | Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом[`VertexDeclaration`](../vertexdeclaration), такое же значение. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator)() | Получает перечислитель для обхода всех полей вершин в этом экземпляре. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode)() | Возвращает хэш-код для этой строки. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring)() | Строковое представление[`VertexDeclaration`](../vertexdeclaration) |

### Смотрите также

* class [VertexField](../vertexfield)
* пространство имен [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->