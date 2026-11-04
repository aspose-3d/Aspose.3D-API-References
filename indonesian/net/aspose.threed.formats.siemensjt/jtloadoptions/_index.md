---
title: "Kelas JtLoadOptions"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Kelas Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. Opsi pemuatan untuk Siemens JT"
type: docs
weight: 1380
url: /id/net/aspose.threed.formats.siemensjt/jtloadoptions/
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
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Menampilkan atau mengatur pengkodean default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan memutuskan pengkodean mana yang akan digunakan. (Diturunkan dari [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Menampilkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. (Diturunkan dari [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Nama file dari adegan yang diekspor/diimpor. Ini opsional, tetapi berguna saat menyerialisasi aset eksternal seperti material OBJ. (Diturunkan dari [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Izinkan pengguna mengatur cara mengelola dependensi eksternal selama pemuatan/penyimpanan. (Diturunkan dari [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Muat informasi PMI dari file JT jika memungkinkan, data akan disimpan sebagai properti "PMI" dari [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Nilai default adalah false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Muat properti dari tabel properti JT sebagai properti Aspose.3D. Nilai default adalah false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. (Diturunkan dari [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Lihat Juga

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


