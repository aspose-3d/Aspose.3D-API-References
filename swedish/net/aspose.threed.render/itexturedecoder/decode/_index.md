---
title: "ITextureDecoder.Decode"
second_title: "Aspose.3D för .NET API‑referens"
description: "ITextureDecoder-metod. Avkoda textur från ström, returnera null om avkodning misslyckas"
type: docs
weight: 10
url: /sv/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Avkoda textur från ström, returnera null om avkodning misslyckas.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Ström för texturdatakälla |
| reverseY | Boolean | Vänd texturen |

### Returvärde

Avkodad texturdata eller null om det inte stöds.

### Undantag

| undantag | villkor |
| --- | --- |
| IOException | Kastas när läsning av data från ström misslyckas |

### Se även

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


