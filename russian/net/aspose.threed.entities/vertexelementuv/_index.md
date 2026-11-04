---
title: "Класс VertexElementUV"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Entities.VertexElementUV класс. Определяет UV‑координаты для указанных компонентов. Геометрия может содержать несколько элементов VertexElementUV, и каждый из них имеет разные TextureMappings"
type: docs
weight: 960
url: /ru/net/aspose.threed.entities/vertexelementuv/
---
## VertexElementUV class

Определяет UV‑координаты для указанных компонентов. Геометрия может иметь несколько элементов `VertexElementUV`, и каждый из них имеет разные [`TextureMapping`](../texturemapping/)s.

```csharp
public class VertexElementUV : VertexElementVector4
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VertexElementUV](vertexelementuv/#constructor)() | Инициализирует новый экземпляр класса `VertexElementUV`. Тип текстурного отображения по умолчанию — Diffuse |
| [VertexElementUV](vertexelementuv/#constructor_1)(TextureMapping) | Инициализирует новый экземпляр класса `VertexElementUV`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Data](../../aspose.threed.entities/vertexelementvector4/data/) { get; } | Получает данные вершины |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Получает данные индексов |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Получает или задает способ отображения элемента. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Получает или задает имя. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Получает или задает способ ссылки на элемент. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Получает тип [`VertexElement`](../vertexelement/) |

## Методы

| Имя | Описание |
| --- | --- |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata)(IEnumerable&lt;Vector2&gt;) |  |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata_1)(IEnumerable&lt;Vector3&gt;) |  |
| override [Clear](../../aspose.threed.entities/vertexelementvector4/clear/)() | Удаляет все элементы из прямых и индексных массивов. |
| [CopyTo](../../aspose.threed.entities/vertexelementvector4/copyto/)(VertexElementVector4) | Копирует данные в указанный элемент. |
| [SetData](../../aspose.threed.entities/vertexelementvector4/setdata/)(Vector4[]) | Загрузить данные |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Загрузить индексы |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Строковое представление элемента вершины. |

### См. также

* class [VertexElementVector4](../vertexelementvector4/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


