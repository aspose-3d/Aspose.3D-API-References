---
title: ITexture1D
second_title: Referensi API Aspose.3D untuk Java
description: Tekstur 1D
type: docs
weight: 252
url: /id/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

Tekstur 1D
## Metode

| Metode | Deskripsi |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Muat konten tekstur dari Bitmap yang ditentukan |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Simpan konten tekstur ke file eksternal. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Simpan konten tekstur ke file eksternal. |
| [toBitmap()](#toBitmap--) | Konversi unit tekstur menjadi instance [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Muat konten tekstur dari Bitmap yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Simpan konten tekstur ke file eksternal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Bitmap hasil untuk disimpan. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Simpan konten tekstur ke file eksternal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | java.lang.String | Nama file untuk disimpan. |
| format | java.lang.String | Format gambar |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Konversi unit tekstur menjadi instance [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
