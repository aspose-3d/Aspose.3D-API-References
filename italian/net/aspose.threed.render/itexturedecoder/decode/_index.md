---
title: "ITextureDecoder.Decode"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo ITextureDecoder. Decodifica la texture dallo stream, restituisce null se la decodifica fallisce"
type: docs
weight: 10
url: /it/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Decodifica la texture dallo stream, restituisce null se la decodifica fallisce.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Stream di origine dei dati della texture |
| reverseY | Boolean | Capovolgi la texture |

### Valore di ritorno

Dati della texture decodificati o null se non supportato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| IOException | Generato quando il lettura dei dati dallo stream fallisce |

### Vedi anche

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


