---
title: "FontFile.FromFile"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode FontFile. Muat FontFile dari nama file"
type: docs
weight: 10
url: /id/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Muat FontFile dari nama file

```csharp
public static FontFile FromFile(string fileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Jalur ke file font |

### Nilai Kembalian

Instansi FontFile

### Exceptions

| pengecualian | kondisi |
| --- | --- |
| IOException | Dilempar ketika gagal membaca dari file. |

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

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


