---
title: ITextureDecoder
second_title: Referencia de API de Aspose.3D para Java
description: El decodificador de textura externa debe implementar esta interfaz para decodificar.
type: docs
weight: 256
url: /es/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

El decodificador de textura externa debe implementar esta interfaz para decodificar.
## Métodos

| Método | Descripción |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Decodificar textura desde el flujo, devolver null si falla la decodificación. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Decodificar textura desde el flujo, devolver null si falla la decodificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Secuencia de origen de datos de textura |
| reverseY | boolean | Voltear la textura |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
