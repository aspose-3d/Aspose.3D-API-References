---
title: "TriMesh.WriteVerticesTo"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TriMesh. Записать данные вершин в указанный поток"
type: docs
weight: 290
url: /ru/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

Запишите данные вершин в указанный поток

```csharp
public void WriteVerticesTo(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который будут записаны данные вершин |

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


