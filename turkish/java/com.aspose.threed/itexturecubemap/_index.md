---
title: "ITextureCubemap"
second_title: "Aspose.3D for Java API Referansı"
description: "Küp harita dokusu"
type: docs
weight: 255
url: /tr/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Küp harita dokusu
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Veriyi belirtilen yüze yükle |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Belirtilen [TextureData](../../com.aspose.threed/texturedata) adresinden doku içeriğini yükle |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Belirtilen dosyalardan doku içeriğini yükle |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Belirtilen yüzeyi belleğe kaydet |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Doku içeriğini belleğe kaydet. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Kübün yüzeylerinin doku içeriğini dış dosyalara kaydet. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Doku birimini [TextureData](../../com.aspose.threed/texturedata) örneğine dönüştür |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Veriyi belirtilen yüze yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Belirtilen [TextureData](../../com.aspose.threed/texturedata) adresinden doku içeriğini yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Belirtilen dosyalardan doku içeriğini yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Belirtilen yüzeyi belleğe kaydet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Doku içeriğini belleğe kaydet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Kaydedilecek sonuç bitmap'i. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Kübün yüzeylerinin doku içeriğini dış dosyalara kaydet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | com.aspose.threed.CubeFaceData<java.lang.String> | Kaydedilecek dosya adları. |
| biçim | java.lang.String | Görüntü biçimi |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Doku birimini [TextureData](../../com.aspose.threed/texturedata) örneğine dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
