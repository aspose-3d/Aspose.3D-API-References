---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode FileSystem. Inisialisasi FileSystem baru yang hanya mengakses direktori lokal. Semua operasi baca/tulis file pada instance FileSystem ini akan dipetakan ke direktori yang ditentukan"
type: docs
weight: 20
url: /id/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Inisialisasi [`FileSystem`](../) baru yang hanya mengakses direktori lokal. Semua operasi baca/tulis file pada instance FileSystem ini akan dipetakan ke direktori yang ditentukan.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| direktori | String | Direktori dalam sistem file fisik Anda sebagai direktori root virtual. |

### Nilai Kembalian

Instance baru dari sistem file untuk menyediakan akses file lokal

### Exceptions

| pengecualian | kondisi |
| --- | --- |
| FileNotFoundException | Dilemparkan ketika direktori tidak dapat ditemukan. |

## Contoh

Kode berikut menunjukkan cara mengimpor file, dan menyediakan file dependensi dalam direktori yang diberikan

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//buat sebuah instance load options dan tentukan sistem file lokal
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//muat file
var scene = Scene.FromFile(inputFile, opt);
```

### Lihat Juga

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


