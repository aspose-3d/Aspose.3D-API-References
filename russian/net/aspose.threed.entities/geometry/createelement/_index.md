---
title: "Geometry.CreateElement"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Geometry. Создает элемент вершины с указанным типом и добавляет его в геометрию"
type: docs
weight: 90
url: /ru/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

Создаёт элемент вершины с указанным типом и добавляет его в геометрию.

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | VertexElementType | Тип элемента вершины |

### Возвращаемое значение

Элемент создан.

## Примечания

Если тип — UV, будет создан [`VertexElementUV`](../../vertexelementuv/) с типом текстурного отображения Diffuse.

### См. также

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

Создаёт элемент вершины с указанным типом и добавляет его в геометрию.

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | VertexElementType | Тип элемента вершины |
| mappingMode | MappingMode | Режим отображения по умолчанию |
| referenceMode | ReferenceMode | Режим ссылки по умолчанию |

### Возвращаемое значение

Элемент создан.

## Примечания

Если тип — UV, будет создан [`VertexElementUV`](../../vertexelementuv/) с типом текстурного отображения Diffuse.

### См. также

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)


