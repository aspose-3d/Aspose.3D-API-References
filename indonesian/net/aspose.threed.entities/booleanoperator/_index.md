---
title: "Kelas BooleanOperator"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Aspose.ThreeD.Entities.BooleanOperator class. Operator Boolean memungkinkan Anda menerapkan operasi Boolean pada dua instance IMeshConvertible"
type: docs
weight: 280
url: /id/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Operator Boolean memungkinkan Anda menerapkan operasi Boolean pada dua instance [`IMeshConvertible`](../imeshconvertible/).

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Konstruktor `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Membuat instance baru `BooleanOperator` dengan dua operand |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Mendapatkan atau mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Operand pertama dari operator Boolean |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapatkan atau mengatur nama. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | Operator Boolean yang digunakan dalam operasi untuk membuat mesh hasil. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Mendapatkan atau mengatur node induk pertama, jika diatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instance geometri |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapatkan koleksi semua properti. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Mendapatkan scene yang dimiliki objek ini |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Operand kedua dari operator Boolean |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Lakukan operasi Boolean pada dua operand |

### Lihat Juga

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


