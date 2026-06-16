---
title: "ITextureDecoder"
second_title: "Aspose.3D for Java API Referansı"
description: "Harici doku çözücüsü, kod çözme için bu arayüzü uygulamalıdır."
type: docs
weight: 256
url: /tr/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Harici doku çözücüsü, kod çözme için bu arayüzü uygulamalıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Akıştan dokuyu çöz, çözümleme başarısız olursa null döndür. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Akıştan dokuyu çöz, çözümleme başarısız olursa null döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Doku veri kaynağı akışı |
| reverseY | boolean | Dokuyu çevir |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
