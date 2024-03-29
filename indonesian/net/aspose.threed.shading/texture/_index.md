---
title: Texture
second_title: Aspose.3D untuk .NET API Referensi
description: Kelas ini mendefinisikan tekstur dari file eksternal.
type: docs
weight: 2350
url: /id/net/aspose.threed.shading/texture/
---
## Texture class

Kelas ini mendefinisikan tekstur dari file eksternal.

```csharp
public class Texture : TextureBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Texture](texture/#constructor)() | Menginisialisasi instance baru dari`Texture` kelas. |
| [Texture](texture/#constructor_1)(string) | Menginisialisasi instance baru dari`Texture` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Mendapat atau menyetel nilai alfa default dari tekstur Ini valid saat[`AlphaSource`](../texturebase/alphasource/) adalahPixelAlpha Nilai default adalah 1.0, rentang nilai yang valid antara 0 dan 1 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Mendapat atau menyetel apakah tekstur mendefinisikan saluran alfa. Nilai defaultnya adalahNone |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | Mendapat atau menyetel konten biner dari tekstur. Konten tekstur yang disematkan adalah opsional, pengguna harus memuat tekstur dari file eksternal jika tidak ada. |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | Mendapat atau menyetel jika mipmap diaktifkan untuk tekstur ini |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | Mendapat atau menyetel file tekstur terkait. |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | Mendapatkan atau menyetel filter untuk pembesaran. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | Mendapat atau menyetel filter untuk minifikasi. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | Mendapatkan atau menyetel filter untuk pengambilan sampel level mip. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapat atau menetapkan nama. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapat koleksi semua properti. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | Mendapat atau mengatur rotasi tekstur |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | Mendapatkan atau menyetel skala UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | Mendapat atau menyetel terjemahan UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | Mendapat atau menyetel mode bungkus tekstur di U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | Mendapat atau menyetel mode bungkus tekstur di V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | Mendapat atau menyetel mode bungkus tekstur di W. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Ini bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Dapatkan nilai properti yang ditentukan |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Menghapus properti dinamis. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Hapus properti yang ditentukan yang diidentifikasi dengan name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Menetapkan nilai properti yang ditentukan |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | Mengatur rotasi UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | Mengatur skala UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | Mengatur terjemahan UV. |

### Lihat juga

* class [TextureBase](../texturebase/)
* ruang nama [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* perakitan [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
