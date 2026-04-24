---
title: ITextureDecoder
second_title: Aspose.3D for Java API-referens
description: Extern texturavkodare bör implementera detta gränssnitt för avkodning.
type: docs
weight: 256
url: /sv/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Extern texturavkodare bör implementera detta gränssnitt för avkodning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Dekoda textur från ström, returnera null om dekodning misslyckas. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Dekoda textur från ström, returnera null om dekodning misslyckas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Texturdatakällans ström |
| reverseY | boolean | Vänd på texturen |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
