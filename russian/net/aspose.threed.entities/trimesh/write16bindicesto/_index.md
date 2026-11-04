---
title: "TriMesh.Write16bIndicesTo"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TriMesh. Записать данные индексов как 16‑битные целые в поток"
type: docs
weight: 270
url: /ru/net/aspose.threed.entities/trimesh/write16bindicesto/
---
## TriMesh.Write16bIndicesTo method

Записать данные индексов как 16‑битные целые в поток

```csharp
public void Write16bIndicesTo(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream |  |

## Примеры

```csharp
//Преобразовать mesh в TriMesh, раскладка автоматически выводится из входного mesh
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//Сохраните его в поток, 115 вершин * 32 байта на вершину
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//Сохраните индексы как ushort в поток, 504 индекса * 2 байта на индекс
triMesh.Write16bIndicesTo(stream);
```

### См. также

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


