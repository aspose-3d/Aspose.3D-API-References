---
title: "ITextureDecoder"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le décodeur de texture externe doit implémenter cette interface pour le décodage."
type: docs
weight: 256
url: /fr/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Le décodeur de texture externe doit implémenter cette interface pour le décodage.
## Méthodes

| Méthode | Description |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Décoder la texture depuis le flux, retourner null si le décodage échoue. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Décoder la texture depuis le flux, retourner null si le décodage échoue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux source de données de texture |
| reverseY | boolean | Inverser la texture |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
