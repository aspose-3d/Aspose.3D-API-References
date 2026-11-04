---
title: "Kelas HalfSpace"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Kelas Aspose.ThreeD.Entities.HalfSpace. HalfSpace merepresentasikan ruang tak hingga yang dipisahkan oleh sebuah bidang; ini dapat digunakan dengan BooleanOperator"
type: docs
weight: 420
url: /id/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` merepresentasikan ruang tak hingga yang dipisahkan oleh sebuah bidang, ini dapat digunakan dengan [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Membuat instance baru dari `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Membuat instance baru dari `HalfSpace` dengan vektor normal yang diberikan dan posisi pada bidang pemotong; |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Mendapatkan atau mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapatkan atau mengatur nama. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | Normal dari bidang pemisah, bidang didefinisikan sebagai N * P + D = 0 dimana N adalah Normal dan P adalah titik mana pun pada bidang. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Mendapatkan atau mengatur node induk pertama, jika diatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instance geometri |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Titik mana pun pada bidang pemisah, bidang didefinisikan sebagai N * P + D = 0 dimana N adalah Normal dan P adalah titik mana pun pada bidang. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapatkan koleksi semua properti. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Mendapatkan scene yang dimiliki objek ini |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti native (Diidentifikasi oleh namanya). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Mendapatkan bounding box dari entitas saat ini dalam sistem koordinat ruang objeknya. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Mendapatkan nilai properti yang ditentukan |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Menghapus properti dinamis. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Menghapus properti yang ditentukan yang diidentifikasi berdasarkan nama |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Mengatur nilai properti yang ditentukan |

### Lihat Juga

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


