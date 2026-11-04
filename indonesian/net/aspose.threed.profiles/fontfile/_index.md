---
title: "Kelas FontFile"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Kelas Aspose.ThreeD.Profiles.FontFile. File font berisi definisi untuk glif yang digunakan untuk membuat profil teks"
type: docs
weight: 1720
url: /id/net/aspose.threed.profiles/fontfile/
---
## FontFile class

File font berisi definisi untuk glif, ini digunakan untuk membuat profil teks.

```csharp
public abstract class FontFile : A3DObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapatkan atau mengatur nama. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapatkan koleksi semua properti. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Muat FontFile dari nama file |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Urai FontFile dari byte |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti native (Diidentifikasi oleh namanya). |
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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


