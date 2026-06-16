---
title: "ITextureEncoder"
second_title: "Référence d'API Aspose.3D pour Java"
description: "L'encodeur de texture externe doit implémenter cette interface pour l'encodage."
type: docs
weight: 257
url: /fr/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

L'encodeur de texture externe doit implémenter cette interface pour l'encodage.
## Méthodes

| Méthode | Description |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Encode les données de texture dans le flux |
| [getFileExtension()](#getFileExtension--) | Nom d'extension de fichier (sans le point) de cet encodeur |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Encode les données de texture dans le flux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Les données de texture à encoder |
| stream | [Stream](../../com.aspose.threed/stream) | Le flux de sortie |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Nom d'extension de fichier (sans le point) de cet encodeur

**Returns:**
java.lang.String - Nom d'extension de fichier (sans le point) de cet encodeur
