---
title: ITextureEncoder
second_title: Referencia de API de Aspose.3D para Java
description: El codificador de textura externa debe implementar esta interfaz para codificar.
type: docs
weight: 257
url: /es/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

El codificador de textura externa debe implementar esta interfaz para codificar.
## Métodos

| Método | Descripción |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Codificar datos de textura en el flujo |
| [getFileExtension()](#getFileExtension--) | Nombre de la extensión de archivo (sin punto) de este codificador |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Codificar datos de textura en el flujo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Los datos de textura a codificar |
| stream | [Stream](../../com.aspose.threed/stream) | El flujo de salida |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Nombre de la extensión de archivo (sin punto) de este codificador

**Returns:**
java.lang.String - Nombre de la extensión de archivo (sin punto) de este codificador
