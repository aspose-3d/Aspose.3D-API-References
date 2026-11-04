---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TriMesh. Загружать вершины из байтов, длина байтов должна быть целым кратным размеру вершины"
type: docs
weight: 160
url: /ru/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

Загрузить вершины из байтов, длина байтов должна быть целым кратным размеру вершины.

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## Примеры

Следующий код показывает, как создать пустой TriMesh и вручную загрузить вершины из необработанных байтов.

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
//создать пустой TriMesh с указанным объявлением вершины
var triMesh = new TriMesh("", vd);
//загружать вершины напрямую из байтов
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
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
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//создать пустой TriMesh с указанным объявлением вершины
var triMesh = new TriMesh("", vd);
//загружать вершины напрямую из байтов
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### См. также

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


