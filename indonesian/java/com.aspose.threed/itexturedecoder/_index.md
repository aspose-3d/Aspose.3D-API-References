---
title: ITextureDecoder
second_title: Referensi API Aspose.3D untuk Java
description: Dekoder tekstur eksternal harus mengimplementasikan antarmuka ini untuk melakukan decoding.
type: docs
weight: 256
url: /id/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Dekoder tekstur eksternal harus mengimplementasikan antarmuka ini untuk melakukan decoding.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Dekode tekstur dari aliran, kembalikan null jika gagal mendekode. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Dekode tekstur dari aliran, kembalikan null jika gagal mendekode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran sumber data tekstur |
| reverseY | boolean | Balikkan tekstur |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
