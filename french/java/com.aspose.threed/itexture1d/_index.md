---
title: "ITexture1D"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Texture 1D"
type: docs
weight: 252
url: /fr/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

Texture 1D
## Méthodes

| Méthode | Description |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Charger le contenu de la texture à partir du Bitmap spécifié |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Enregistrez le contenu de la texture dans un fichier externe. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Enregistrez le contenu de la texture dans un fichier externe. |
| [toBitmap()](#toBitmap--) | Convertir l'unité de texture en instance [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Charger le contenu de la texture à partir du Bitmap spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Enregistrez le contenu de la texture dans un fichier externe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Bitmap résultat à enregistrer. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Enregistrez le contenu de la texture dans un fichier externe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Nom de fichier à enregistrer. |
| format | java.lang.String | Format d'image |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Convertir l'unité de texture en instance [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
