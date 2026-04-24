---
title: ITextureDecoder
second_title: Aspose.3D for Java API Reference
description: Il decoder di texture esterno dovrebbe implementare questa interfaccia per la decodifica.
type: docs
weight: 256
url: /it/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Il decoder di texture esterno dovrebbe implementare questa interfaccia per la decodifica.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Decodifica la texture dallo stream, restituisce null se il decodifica fallisce. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Decodifica la texture dallo stream, restituisce null se il decodifica fallisce.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flusso di origine dati della texture |
| reverseY | boolean | Capovolgi la texture |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
