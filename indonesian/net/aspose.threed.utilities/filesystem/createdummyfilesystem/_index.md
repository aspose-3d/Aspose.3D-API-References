---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode FileSystem. Membuat sistem file dummy operasi baca/tulis adalah operasi dummy"
type: docs
weight: 10
url: /id/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Buat sistem file dummy, operasi baca/tulis adalah operasi dummy.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Nilai Kembalian

Sebuah sistem file dummy

## Contoh

Kode berikut menunjukkan cara mengekspor file ke memori, dan mengabaikan semua pembuatan file yang bergantung.

```csharp
//buat sebuah adegan dengan material
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//buat opsi penyimpanan dan tentukan sistem file, sehingga file yang bergantung akan ditulis ke memori
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//Nama file material obj terkait dengan nama file obj, jadi kita membutuhkan nama yang eksplisit.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Lihat Juga

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


