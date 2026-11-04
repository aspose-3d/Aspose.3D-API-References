---
title: "FileSystem.CreateZipFileSystem"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "metode FileSystem. Buat sistem file untuk menyediakan akses hanya-baca ke file zip yang ditentukan atau aliran zip. Sistem file akan dibuang setelah operasi buka/penyimpanan."
type: docs
weight: 40
url: /id/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Buat sistem file untuk menyediakan akses hanya-baca ke file zip yang ditentukan atau aliran zip. Sistem file akan dibuang setelah operasi buka/penyimpanan.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran untuk mengakses file zip |
| baseDir | String | Direktori dasar di dalam file zip. |

### Nilai Kembalian

Sistem file zip

### Exceptions

| pengecualian | kondisi |
| --- | --- |
| IOException | Dilemparkan ketika gagal membaca dari aliran. |

## Catatan

Ini adalah sistem file hanya-baca, jadi tidak ada operasi penulisan yang didukung.

## Contoh

Kode berikut menunjukkan cara mengimpor file, dan menyediakan file dependensi dalam file arsip zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//buat sebuah instance load options dan tentukan sistem file zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//muat file
var scene = Scene.FromFile(inputFile, opt);
```

### Lihat Juga

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Sistem file untuk menyediakan akses hanya-baca ke file zip yang ditentukan atau aliran zip. Sistem file akan dibuang setelah operasi buka/penyimpanan.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file untuk file zip. |

### Nilai Kembalian

Sistem file zip

### Exceptions

| pengecualian | kondisi |
| --- | --- |
| IOException | Dilemparkan ketika gagal membaca dari aliran. |

## Contoh

Kode berikut menunjukkan cara mengimpor file, dan menyediakan file dependensi dalam file arsip zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//buat sebuah instance load options dan tentukan sistem file zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//muat file
var scene = Scene.FromFile(inputFile, opt);
```

### Lihat Juga

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


