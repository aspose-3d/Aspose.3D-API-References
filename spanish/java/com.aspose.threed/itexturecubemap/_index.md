---
title: ITextureCubemap
second_title: Referencia de API de Aspose.3D para Java
description: Textura de mapa cúbico
type: docs
weight: 255
url: /es/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Textura de mapa cúbico
## Métodos

| Método | Descripción |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Cargar los datos en la cara especificada |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Cargar el contenido de la textura desde el [TextureData](../../com.aspose.threed/texturedata) especificado |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Cargar contenido de textura desde archivos especificados |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Guardar el lado especificado en memoria |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Guardar el contenido de la textura en memoria. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Guardar el contenido de textura de los lados del cubo en archivos externos. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Convertir la unidad de textura a una instancia de [TextureData](../../com.aspose.threed/texturedata) |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Cargar los datos en la cara especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Cargar el contenido de la textura desde el [TextureData](../../com.aspose.threed/texturedata) especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Cargar contenido de textura desde archivos especificados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Guardar el lado especificado en memoria

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Guardar el contenido de la textura en memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Bitmap resultante para guardar. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Guardar el contenido de textura de los lados del cubo en archivos externos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | com.aspose.threed.CubeFaceData<java.lang.String> | Nombres de archivo para guardar. |
| formato | java.lang.String | Formato de imagen |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Convertir la unidad de textura a una instancia de [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
