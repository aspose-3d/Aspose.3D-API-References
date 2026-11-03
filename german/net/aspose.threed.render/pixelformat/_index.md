---
title: "Enum PixelFormat"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.PixelFormat Enum. Das Pixel-Format, das in der Textureinheit verwendet wird"
type: docs
weight: 2210
url: /de/net/aspose.threed.render/pixelformat/
---
## PixelFormat enumeration

Das Pixel-Format, das in der Textureinheit verwendet wird.

```csharp
public enum PixelFormat
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Unknown | `0` | Unbekanntes Pixel-Format. |
| L8 | `1` | 8-Bit-Pixel-Format, alle Bits Luminanz. |
| L16 | `2` | 16-Bit-Pixel-Format, alle Bits Luminanz. |
| A8 | `3` | 8-Bit-Pixel-Format, alle Bits Alpha. |
| A4L4 | `4` | 8-Bit-Pixel-Format, 4 Bits Alpha, 4 Bits Luminanz. |
| BYTE_LA | `5` | 2-Byte-Pixel-Format, 1 Byte Luminanz, 1 Byte Alpha |
| R5G6B5 | `6` | 16-Bit-Pixel-Format, 5 Bits Rot, 6 Bits Grün, 5 Bits Blau. |
| B5G6R5 | `7` | 16-Bit-Pixel-Format, 5 Bits Rot, 6 Bits Grün, 5 Bits Blau. |
| R3G3B2 | `8` | 8-Bit-Pixel-Format, 2 Bits Blau, 3 Bits Grün, 3 Bits Rot. |
| A4R4G4B4 | `9` | 16-Bit-Pixel-Format, 4 Bits für Alpha, Rot, Grün und Blau. |
| A1R5G5B5 | `10` | 16-Bit-Pixel-Format, 5 Bits für Blau, Grün, Rot und 1 Bit für Alpha. |
| R8G8B8 | `11` | 24-Bit-Pixel-Format, 8 Bits für Rot, Grün und Blau. |
| B8G8R8 | `12` | 24-Bit-Pixel-Format, 8 Bits für Blau, Grün, Rot. |
| A8R8G8B8 | `13` | 32-Bit-Pixel-Format, 8 Bits für Alpha, Rot, Grün und Blau. |
| A8B8G8R8 | `14` | 32-Bit-Pixel-Format, 8 Bits für Blau, Grün, Rot und Alpha. |
| B8G8R8A8 | `15` | 32-Bit-Pixel-Format, 8 Bits für Blau, Grün, Rot und Alpha. |
| R8G8B8A8 | `16` | 32-Bit-Pixel-Format, 8 Bits für Rot, Grün, Blau und Alpha. |
| X8R8G8B8 | `17` | 32-Bit-Pixel-Format, 8 Bit für Rot, 8 Bit für Grün, 8 Bit für Blau wie A8R8G8B8, aber Alpha wird verworfen |
| X8B8G8R8 | `18` | 32-Bit-Pixel-Format, 8 Bit für Blau, 8 Bit für Grün, 8 Bit für Rot wie A8B8G8R8, aber Alpha wird verworfen |
| A2R10G10B10 | `19` | 32-Bit-Pixel-Format, 2 Bit für Alpha, 10 Bit für Rot, Grün und Blau. |
| A2B10G10R10 | `20` | 32-Bit-Pixel-Format, 10 Bit für Blau, Grün und Rot, 2 Bit für Alpha. |
| DXT1 | `21` | DDS (DirectDraw Surface) DXT1-Format. |
| DXT2 | `22` | DDS (DirectDraw Surface) DXT2-Format. |
| DXT3 | `23` | DDS (DirectDraw Surface) DXT3-Format. |
| DXT4 | `24` | DDS (DirectDraw Surface) DXT4-Format. |
| DXT5 | `25` | DDS (DirectDraw Surface) DXT5-Format. |
| FLOAT16_R | `26` | 16-Bit-Pixel-Format, 16 Bit (Float) für Rot |
| FLOAT16_RGB | `27` | 48-Bit-Pixel-Format, 16 Bit (Float) für Rot, 16 Bit (Float) für Grün, 16 Bit (Float) für Blau |
| FLOAT16_RGBA | `28` | 64-Bit-Pixel-Format, 16 Bit (Float) für Rot, 16 Bit (Float) für Grün, 16 Bit (Float) für Blau, 16 Bit (Float) für Alpha |
| FLOAT32_R | `29` | 32-Bit-Pixel-Format, 32 Bit (Float) für Rot |
| FLOAT32_RGB | `30` | 96-Bit-Pixel-Format, 32 Bit (Float) für Rot, 32 Bit (Float) für Grün, 32 Bit (Float) für Blau |
| FLOAT32_RGBA | `31` | 128-Bit-Pixel-Format, 32 Bit (Float) für Rot, 32 Bit (Float) für Grün, 32 Bit (Float) für Blau, 32 Bit (Float) für Alpha |
| FLOAT16_GR | `32` | 32-Bit, 2-Kanal s10e5 Fließkomma-Pixel-Format, 16-Bit Grün, 16-Bit Rot |
| FLOAT32_GR | `33` | 64-Bit, 2-Kanal Fließkomma-Pixel-Format, 32-Bit Grün, 32-Bit Rot |
| DEPTH | `34` | Depth-Texturformat. |
| SHORT_RGBA | `35` | 64-Bit-Pixel-Format, 16 Bit für Rot, Grün, Blau und Alpha |
| SHORT_GR | `36` | 32-Bit-Pixel-Format, 16-Bit Grün, 16-Bit Rot |
| SHORT_RGB | `37` | 48-Bit-Pixel-Format, 16 Bit für Rot, Grün und Blau |
| R32_UINT | `38` | 32-Bit-Pixel-Format, 32 Bit Rot (unsigned int). |
| R32G32_UINT | `39` | 64-Bit-Pixel-Format, 32 Bit Rot (unsigned int), 32 Bit Blau (unsigned int). |
| R32G32B32A32_UINT | `40` | 128-Bit-Pixel-Format, 32 Bit Rot (unsigned int), 32 Bit Blau (unsigned int), 32 Bit Grün (unsigned int), 32 Bit Alpha (unsigned int). |
| R8 | `41` | 8-Bit-Pixel-Format, alle Bits Rot. |
| G8 | `42` | 8-Bit-Pixel-Format, alle Bits grün. |
| B8 | `43` | 8-Bit-Pixel-Format, alle Bits blau. |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


