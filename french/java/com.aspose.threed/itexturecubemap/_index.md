---
title: "ITextureCubemap"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Texture de cube map"
type: docs
weight: 255
url: /fr/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Texture de cube map
## Méthodes

| Méthode | Description |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Charger les données dans la face spécifiée |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Charger le contenu de la texture à partir du [TextureData](../../com.aspose.threed/texturedata) spécifié |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Charger le contenu de la texture à partir des fichiers spécifiés |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Enregistrer le côté spécifié en mémoire |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Enregistrer le contenu de la texture en mémoire. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Enregistrer le contenu de la texture des côtés du cube dans des fichiers externes. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Convertir l'unité de texture en instance [TextureData](../../com.aspose.threed/texturedata) |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Charger les données dans la face spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Charger le contenu de la texture à partir du [TextureData](../../com.aspose.threed/texturedata) spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Charger le contenu de la texture à partir des fichiers spécifiés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Enregistrer le côté spécifié en mémoire

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Enregistrer le contenu de la texture en mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Bitmap résultat à enregistrer. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Enregistrer le contenu de la texture des côtés du cube dans des fichiers externes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | com.aspose.threed.CubeFaceData<java.lang.String> | Noms de fichiers à enregistrer. |
| format | java.lang.String | Format d'image |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Convertir l'unité de texture en instance [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
