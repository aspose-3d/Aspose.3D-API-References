---
title: "Mesh.op_BitwiseOr"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode Mesh. Hitung gabungan dua mesh"
type: docs
weight: 140
url: /id/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Hitung gabungan dua mesh

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | Mesh | Mesh pertama |
| b | Mesh | Mesh kedua |

### Nilai Kembalian

Mesh hasil

## Contoh

Kode berikut menunjukkan cara menggabungkan dua mesh menjadi satu mesh:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Lihat Juga

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


