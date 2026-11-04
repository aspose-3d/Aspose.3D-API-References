---
title: "Kelas CenterLineProfile"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Kelas Aspose.ThreeD.Profiles.CenterLineProfile. Profil garis tengah yang kompatibel dengan IFC"
type: docs
weight: 1690
url: /id/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

Profil garis tengah yang kompatibel dengan IFC

```csharp
public class CenterLineProfile : Profile
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | Membuat `CenterLineProfile` baru dengan kurva yang ditentukan sebagai garis tengah. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | Kurva garis tengah dari profil |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Mendapatkan atau mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapatkan atau mengatur nama. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Mendapatkan atau mengatur node induk pertama, jika diatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instance geometri |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapatkan koleksi semua properti. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Mendapatkan scene yang dimiliki objek ini |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | Ketebalan yang diterapkan sepanjang garis tengah |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti native (Diidentifikasi oleh namanya). |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Mendapatkan bounding box dari entitas saat ini dalam sistem koordinat ruang objeknya. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Mendapatkan nilai properti yang ditentukan |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Menghapus properti dinamis. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Menghapus properti yang ditentukan yang diidentifikasi berdasarkan nama |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Mengatur nilai properti yang ditentukan |

### Lihat Juga

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


