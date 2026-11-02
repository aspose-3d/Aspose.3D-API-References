---
title: "ITextureDecoder"
second_title: "Aspose.3D voor Java API-referentie"
description: "Externe texture-decoder moet deze interface implementeren voor decodering."
type: docs
weight: 256
url: /nl/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Externe texture-decoder moet deze interface implementeren voor decodering.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Decodeer textuur van stream, retourneer null als decodering mislukt. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Decodeer textuur van stream, retourneer null als decodering mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Textuurgegevensstroom |
| reverseY | boolean | Keer de textuur om. |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
