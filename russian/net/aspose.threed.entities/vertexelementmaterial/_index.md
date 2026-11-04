---
title: "Класс VertexElementMaterial"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.VertexElementMaterial. Определяет индекс материала для указанных компонентов. Узел может иметь несколько материалов; VertexElementMaterial используется для рендеринга разных частей геометрии разными материалами."
type: docs
weight: 880
url: /ru/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

Определяет индекс материала для указанных компонентов. Узел может иметь несколько материалов, `VertexElementMaterial` используется для рендеринга разных частей геометрии разными материалами.

```csharp
public class VertexElementMaterial : VertexElement
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | Инициализирует новый экземпляр класса `VertexElementMaterial`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Получает данные индексов |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Получает или задает способ отображения элемента. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Получает или задает имя. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Получает или задает способ ссылки на элемент. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Получает тип [`VertexElement`](../vertexelement/) |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | Удаляет все элементы из прямых и индексных массивов. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Загрузить индексы |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Строковое представление элемента вершины. |

## Примеры

Следующий код показывает, как назначить разные материалы разным граням коробки.

```csharp
// Создайте сетку коробки (коробка состоит из 6 плоскостей)
Mesh box = (new Box()).ToMesh();
// Создайте элемент материала на этой сетке
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// И укажите разный индекс материала для каждой плоскости
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### См. также

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


