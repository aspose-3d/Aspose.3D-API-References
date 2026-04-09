---
title: ITextureCubemap
second_title: Referensi API Aspose.3D untuk Java
description: Tekstur peta kubus
type: docs
weight: 255
url: /id/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Tekstur peta kubus
## Metode

| Metode | Deskripsi |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Muat data ke wajah yang ditentukan |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Muat konten tekstur dari [TextureData](../../com.aspose.threed/texturedata) yang ditentukan |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Muat konten tekstur dari file yang ditentukan |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Simpan sisi yang ditentukan ke memori |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Simpan konten tekstur ke memori. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Simpan konten tekstur sisi kubus ke file eksternal. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Konversi unit tekstur menjadi instance [TextureData](../../com.aspose.threed/texturedata) |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Muat data ke wajah yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Muat konten tekstur dari [TextureData](../../com.aspose.threed/texturedata) yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Muat konten tekstur dari file yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Simpan sisi yang ditentukan ke memori

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Simpan konten tekstur ke memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Bitmap hasil untuk disimpan. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Simpan konten tekstur sisi kubus ke file eksternal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | com.aspose.threed.CubeFaceData<java.lang.String> | Nama file untuk disimpan. |
| format | java.lang.String | Format gambar |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Konversi unit tekstur menjadi instance [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
