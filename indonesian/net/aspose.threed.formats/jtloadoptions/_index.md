---
title: "Kelas JtLoadOptions"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Kelas Aspose.ThreeD.Formats.JtLoadOptions. Opsi pemuatan untuk Siemens JT"
type: docs
weight: 1310
url: /id/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

Opsi pemuatan untuk Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Mendapatkan atau mengatur enkoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan menentukan enkoding yang digunakan. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Nama file dari adegan ekspor/impor. Ini opsional, tetapi berguna saat menyerialisasi aset eksternal seperti material OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama memuat/menyimpan. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | Muat informasi PMI dari file JT jika memungkinkan, data akan disimpan sebagai properti "PMI" dari [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Nilai default adalah false. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | Muat properti dari tabel properti JT sebagai properti Aspose.3D. Nilai default adalah false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |

### Lihat Juga

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


