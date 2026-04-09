---
title: ITextureEncoder
second_title: Aspose.3D for Java API Reference
description: Il codificatore di texture esterno dovrebbe implementare questa interfaccia per la codifica.
type: docs
weight: 257
url: /it/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

Il codificatore di texture esterno dovrebbe implementare questa interfaccia per la codifica.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Codifica i dati della texture nello stream |
| [getFileExtension()](#getFileExtension--) | Nome dell'estensione del file (senza punto) di questo encoder |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Codifica i dati della texture nello stream

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | I dati della texture da codificare |
| stream | [Stream](../../com.aspose.threed/stream) | Il flusso di output |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Nome dell'estensione del file (senza punto) di questo encoder

**Returns:**
java.lang.String - Nome dell'estensione del file (senza punto) di questo encoder
