---
title: "ITextureDecoder.Decode"
second_title: "Aspose.3D voor .NET API-referentie"
description: "ITextureDecoder methode. Decodeer texture van stream, retourneer null als decodering mislukt"
type: docs
weight: 10
url: /nl/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Decodeer texture vanuit stream, retourneer null als decodering mislukt.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Texture-databronstream |
| reverseY | Boolean | Spiegel de texture |

### Retourwaarde

Gedecodeerde texture-gegevens of null als niet ondersteund.

### Exceptions

| exceptie | conditie |
| --- | --- |
| IOException | Wordt gegooid wanneer het lezen van gegevens uit de stream mislukt. |

### Zie ook

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


