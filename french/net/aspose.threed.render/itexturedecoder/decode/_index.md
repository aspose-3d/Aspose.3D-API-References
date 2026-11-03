---
title: "ITextureDecoder.Decode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode ITextureDecoder. Décode la texture depuis le flux, renvoie null si le décodage échoue"
type: docs
weight: 10
url: /fr/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Décode la texture depuis le flux, retourne null si le décodage échoue.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux source de données de texture |
| reverseY | Boolean | Inverser la texture |

### Valeur de retour

Données de texture décodées ou null si non pris en charge.

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancée lorsque la lecture des données depuis le flux échoue |

### Voir aussi

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


