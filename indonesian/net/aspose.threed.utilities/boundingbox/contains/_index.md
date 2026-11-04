---
title: "BoundingBox.Contains"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode BoundingBox. Memeriksa apakah titik p berada di dalam kotak pembatas"
type: docs
weight: 100
url: /id/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Memeriksa apakah titik p berada di dalam kotak pembatas

```csharp
public bool Contains(Vector3 p)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | Vector3 | Titik untuk diuji |

### Nilai Kembalian

Benar jika titik berada di dalam kotak pembatas

## Contoh

Kode berikut menunjukkan cara memeriksa apakah titik berada di dalam kotak pembatas.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Lihat Juga

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Kotak pembatas untuk memeriksa apakah berada di dalam kotak pembatas saat ini.

```csharp
public bool Contains(BoundingBox bbox)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Lihat Juga

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


