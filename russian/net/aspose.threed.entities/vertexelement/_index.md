---
title: "Класс VertexElement"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.VertexElement. Базовый класс элементов вершин. Тип элемента вершины определяется VertexElementType. VertexElement описывает, как элемент вершины отображается на геометрическую поверхность и как информация о отображении располагается в памяти. VertexElement содержит нормали, UV‑координаты или другую информацию."
type: docs
weight: 820
url: /ru/net/aspose.threed.entities/vertexelement/
---
## VertexElement class

Базовый класс элементов вершины. Тип элемента вершины определяется VertexElementType. VertexElement описывает, как элемент вершины отображается на поверхность геометрии и как информация о отображении размещается в памяти. VertexElement содержит нормали, UV‑координаты или другие виды информации.

```csharp
public abstract class VertexElement : IIndexedVertexElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Получает данные индексов |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Получает или задает способ отображения элемента. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Получает или задает имя. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Получает или задает способ ссылки на элемент. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Получает тип `VertexElement` |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Clear](../../aspose.threed.entities/vertexelement/clear/)() | Очищает все данные этого элемента вершины. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Загрузить индексы |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Строковое представление элемента вершины. |

### См. также

* interface [IIndexedVertexElement](../iindexedvertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


