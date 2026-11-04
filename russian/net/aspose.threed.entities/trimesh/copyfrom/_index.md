---
title: "TriMesh.CopyFrom"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TriMesh. Скопировать TriMesh из входных данных с новой раскладкой вершин"
type: docs
weight: 20
url: /ru/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

Скопировать [`TriMesh`](../) из входных данных с новой раскладкой вершин

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | TriMesh | Входной TriMesh для копирования |
| vd | VertexDeclaration | Новая декларация вершин выходного TriMesh |

### Возвращаемое значение

Новый экземпляр TriMesh с новой декларацией вершин.

## Примеры

```csharp
//Определите объявление вершины как {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Преобразовать mesh в TriMesh, раскладка автоматически выводится из входного mesh
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//Теперь создать новый TriMesh из старого TriMesh, используя явную раскладку памяти, определённую vd
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### См. также

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


