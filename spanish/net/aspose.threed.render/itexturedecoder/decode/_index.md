---
title: "ITextureDecoder.Decode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método ITextureDecoder. Decodifica la textura desde el flujo y devuelve null si falla la decodificación"
type: docs
weight: 10
url: /es/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Decodifica la textura desde el flujo, devuelve null si falla la decodificación.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de origen de datos de textura |
| reverseY | Boolean | Voltear la textura |

### Valor de retorno

Datos de textura decodificados o null si no es compatible.

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Se lanza cuando falla la lectura de datos del flujo |

### Ver también

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


