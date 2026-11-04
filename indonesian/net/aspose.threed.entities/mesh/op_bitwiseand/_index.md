---
title: "Mesh.op_BitwiseAnd"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode Mesh. Hitung irisan dua mesh"
type: docs
weight: 130
url: /id/net/aspose.threed.entities/mesh/op_bitwiseand/
---
## Mesh BitwiseAnd operator

Hitung irisan dua mesh

```csharp
public static Mesh operator &(Mesh a, Mesh b)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | Mesh | Mesh pertama |
| b | Mesh | Mesh kedua |

### Nilai Kembalian

Mesh hasil

## Contoh

Kode berikut menunjukkan cara menghitung selisih dua mesh:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 & box2;
```

### Lihat Juga

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


