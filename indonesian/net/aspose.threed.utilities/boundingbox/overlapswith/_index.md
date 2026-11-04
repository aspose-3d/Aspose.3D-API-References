---
title: "BoundingBox.OverlapsWith"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode BoundingBox. Memeriksa apakah kotak pembatas saat ini tumpang tindih dengan kotak pembatas yang ditentukan"
type: docs
weight: 140
url: /id/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Memeriksa apakah kotak pembatas saat ini tumpang tindih dengan kotak pembatas yang ditentukan.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kotak | BoundingBox | Kotak pembatas lain untuk diuji |

### Nilai Kembalian

Benar jika kotak pembatas saat ini tumpang tindih dengan yang diberikan.

## Contoh

Kode berikut menunjukkan cara memeriksa apakah dua kotak pembatas tumpang tindih satu sama lain.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Lihat Juga

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


