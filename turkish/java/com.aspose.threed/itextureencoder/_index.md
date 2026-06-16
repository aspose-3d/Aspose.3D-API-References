---
title: "ITextureEncoder"
second_title: "Aspose.3D for Java API Referansı"
description: "Harici doku kodlayıcısı, kodlama için bu arayüzü uygulamalıdır."
type: docs
weight: 257
url: /tr/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

Harici doku kodlayıcısı, kodlama için bu arayüzü uygulamalıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Doku verisini akışa kodla |
| [getFileExtension()](#getFileExtension--) | Bu kodlayıcının dosya uzantısı adı (noktasız) |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Doku verisini akışa kodla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Kodlanacak doku verisi |
| stream | [Stream](../../com.aspose.threed/stream) | Çıktı akışı |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Bu kodlayıcının dosya uzantısı adı (noktasız)

**Returns:**
java.lang.String - Bu kodlayıcının dosya uzantısı adı (noktasız)
