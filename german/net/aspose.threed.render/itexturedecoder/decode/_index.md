---
title: "ITextureDecoder.Decode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "ITextureDecoder-Methode. Dekodiert Textur aus Stream, gibt null zurück, wenn die Dekodierung fehlschlägt."
type: docs
weight: 10
url: /de/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Dekodiere Textur aus Stream, gib null zurück, wenn das Dekodieren fehlschlägt.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Textur-Daten-Stream |
| reverseY | Boolean | Spiegle die Textur. |

### Rückgabewert

Dekodierte Texturdaten oder null, wenn nicht unterstützt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen von Daten aus dem Stream fehlschlägt. |

### Siehe auch

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


