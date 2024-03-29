---
title: Pose
second_title: Aspose.3D untuk .NET API Referensi
description: Pose digunakan untuk menyimpan matriks transformasi saat geometri dikuliti. Pose adalah sekumpulanBonePose./bonepose/  setiapBonePose./bonepose/ menyimpan informasi transformasi konkret dari node tulang.
type: docs
weight: 1490
url: /id/net/aspose.threed/pose/
---
## Pose class

Pose digunakan untuk menyimpan matriks transformasi saat geometri dikuliti. Pose adalah sekumpulan[`BonePose`](../bonepose/) , setiap[`BonePose`](../bonepose/) menyimpan informasi transformasi konkret dari node tulang.

```csharp
public class Pose : A3DObject
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Pose](pose/#constructor)() | Menginisialisasi instance baru dari`Pose` kelas. |
| [Pose](pose/#constructor_1)(string) | Menginisialisasi instance baru dari`Pose` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | Mendapatkan semuanya[`BonePose`](../bonepose/) . |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapat atau menetapkan nama. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | Mendapat atau menyetel jenis pose. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapat koleksi semua properti. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | Menyimpan matriks transformasi pose untuk simpul tulang yang diberikan. Matriks transformasi global tersirat. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | Menyimpan matriks transformasi pose untuk simpul tulang yang diberikan. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Ini bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Dapatkan nilai properti yang ditentukan |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Menghapus properti dinamis. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Hapus properti yang ditentukan yang diidentifikasi dengan name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Menetapkan nilai properti yang ditentukan |

### Lihat juga

* class [A3DObject](../a3dobject/)
* ruang nama [Aspose.ThreeD](../../aspose.threed/)
* perakitan [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
