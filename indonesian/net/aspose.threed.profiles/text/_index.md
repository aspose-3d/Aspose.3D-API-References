---
title: "Kelas Text"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Kelas Aspose.ThreeD.Profiles.Text. Profil teks profil ini menjelaskan kontur menggunakan font dan teks"
type: docs
weight: 1820
url: /id/net/aspose.threed.profiles/text/
---
## Text class

Profil teks, profil ini menjelaskan kontur menggunakan font dan teks.

```csharp
public class Text : Profile
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Text](text/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | Konten teks |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Mendapatkan atau mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | Font teks. |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | Skala ukuran font. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapatkan atau mengatur nama. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Mendapatkan atau mengatur node induk pertama, jika diatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instance geometri |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapatkan koleksi semua properti. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Mendapatkan scene yang dimiliki objek ini |

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

## Contoh

Kode berikut menunjukkan cara membuat mesh 3D dari teks menggunakan file font yang ditentukan.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Lihat Juga

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


