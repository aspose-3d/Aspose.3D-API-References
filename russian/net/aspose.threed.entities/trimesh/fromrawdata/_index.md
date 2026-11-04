---
title: "TriMesh.FromRawData"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TriMesh. Создать TriMesh из необработанных данных"
type: docs
weight: 40
url: /ru/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

Создать TriMesh из необработанных данных

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vd | VertexDeclaration | Объявление вершины, должно содержать как минимум одно поле. |
| вершины | Byte[] | Входные данные вершины, минимальная длина массива вершин должна быть больше или равна размеру объявления вершины |
| индексы | Int32[] | Индексы треугольников |
| generateVertexMapping | Boolean | Создать [`Vertex`](../../../aspose.threed.utilities/vertex/) для каждой вершины, что не требуется только для сериализации/десериализации. |

### Возвращаемое значение

Экземпляр [`TriMesh`](../), который инкапсулировал входной массив байтов.

## Примечания

Возвращённый TriMesh не будет копировать входной массив байтов для повышения производительности, внешние изменения массива будут отражаться в этом экземпляре.

## Примеры

Следующий код показывает, как построить TriMesh из необработанных байтов, это полезно при создании собственного 3D‑формата

```csharp
var indices = new int[] { 0,  1,  2 };
var vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### См. также

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


