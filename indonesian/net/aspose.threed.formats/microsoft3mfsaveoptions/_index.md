---
title: "Kelas Microsoft3MFSaveOptions"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Aspose.ThreeD.Formats.Microsoft3MFSaveOptions class. Opsi penyimpanan untuk file Microsoft 3MF"
type: docs
weight: 1350
url: /id/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Opsi penyimpanan untuk file Microsoft 3MF.

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | Buat sebuah `Microsoft3MFSaveOptions` |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | Tandai semua geometri dalam adegan agar dapat dicetak. Atau Anda dapat secara manual menandai node agar dapat dicetak dengan [`SetBuildable`](../microsoft3mfformat/setbuildable/) Nilai default adalah true |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | Aktifkan kompresi pada file 3mf output Nilai default adalah true |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Mendapatkan atau mengatur enkoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan enkoding yang digunakan. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Coba salin tekstur yang digunakan dalam adegan ke direktori output. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Nama file dari adegan ekspor/impor. Ini opsional, tetapi berguna saat menyerialisasi aset eksternal seperti material OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama memuat/menyimpan. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |

### Lihat Juga

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


