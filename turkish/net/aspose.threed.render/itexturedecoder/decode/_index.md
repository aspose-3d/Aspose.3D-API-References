---
title: "ITextureDecoder.Decode"
second_title: "Aspose.3D for .NET API Referansı"
description: "ITextureDecoder yöntemi. Akıştan dokuyu çözer, çözülemezse null döndürür"
type: docs
weight: 10
url: /tr/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Akıştan doku çöz, başarısız olursa null döndür.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Stream | Doku veri kaynağı akışı |
| reverseY | Boolean | Dokuyu çevir |

### Dönüş Değeri

Çözülen doku verisi veya desteklenmiyorsa null.

### İstisnalar

| istisna | koşul |
| --- | --- |
| IOException | Akıştan veri okunamadığında fırlatılır. |

### Ayrıca Bakınız

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


