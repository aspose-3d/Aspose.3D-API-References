---
title: "Mesh.Triangulate"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode Mesh. Mengembalikan mesh yang ditriangulasi"
type: docs
weight: 120
url: /id/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Kembalikan mesh yang ditriangulasi

```csharp
public Mesh Triangulate()
```

### Nilai Kembalian

Mesh saat ini jika sudah ditriangulasi, jika tidak mesh baru yang ditriangulasi akan dihitung dan dikembalikan

## Contoh

Kode berikut menunjukkan cara mentriangulasi mesh:

```csharp
//Mesh bidang hanya memiliki satu poligon dengan 4 titik kontrol
var mesh = (new Plane()).ToMesh();
//Setelah ditriangulasi, persegi panjang mesh baru akan menjadi 2 segitiga.
var triangulated = mesh.Triangulate();
```

### Lihat Juga

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


