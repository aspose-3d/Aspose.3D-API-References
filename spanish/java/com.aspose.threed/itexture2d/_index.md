---
title: ITexture2D
second_title: Referencia de API de Aspose.3D para Java
description: Textura 2D
type: docs
weight: 253
url: /es/java/com.aspose.threed/itexture2d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture2D extends ITextureUnit
```

Textura 2D
## Métodos

| Método | Descripción |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Cargar el contenido de la textura desde el Bitmap especificado |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Guardar el contenido de la textura en un archivo externo. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Guardar el contenido de la textura en un archivo externo. |
| [toBitmap()](#toBitmap--) | Convertir la unidad de textura a una instancia de [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Cargar el contenido de la textura desde el Bitmap especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Guardar el contenido de la textura en un archivo externo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Bitmap resultante para guardar. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Guardar el contenido de la textura en un archivo externo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | Nombre de archivo para guardar. |
| formato | java.lang.String | Formato de imagen |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Convertir la unidad de textura a una instancia de [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
