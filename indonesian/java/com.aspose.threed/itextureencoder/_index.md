---
title: ITextureEncoder
second_title: Referensi API Aspose.3D untuk Java
description: Enkoder tekstur eksternal harus mengimplementasikan antarmuka ini untuk melakukan encoding.
type: docs
weight: 257
url: /id/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

Enkoder tekstur eksternal harus mengimplementasikan antarmuka ini untuk melakukan encoding.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Menyandikan data tekstur ke dalam aliran. |
| [getFileExtension()](#getFileExtension--) | Nama ekstensi file (tanpa titik) dari encoder ini |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Menyandikan data tekstur ke dalam aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Data tekstur yang akan disandikan. |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran keluaran |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Nama ekstensi file (tanpa titik) dari encoder ini

**Returns:**
java.lang.String - Nama ekstensi file (tanpa titik) dari encoder ini
