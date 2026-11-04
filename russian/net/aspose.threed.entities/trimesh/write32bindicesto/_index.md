---
title: "TriMesh.Write32bIndicesTo"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TriMesh. Записать данные индексов как 32‑битные целые в поток"
type: docs
weight: 280
url: /ru/net/aspose.threed.entities/trimesh/write32bindicesto/
---
## TriMesh.Write32bIndicesTo method

Запишите данные индексов как 32‑битное целое в поток

```csharp
public void Write32bIndicesTo(Stream stream)
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
triMesh.Write32bIndicesTo(stream);
```

### См. также

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


