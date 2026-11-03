---
title: "Απαρίθμηση PixelFormat"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Απαρίθμηση Aspose.ThreeD.Render.PixelFormat. Η μορφή pixel που χρησιμοποιείται στη μονάδα υφής."
type: docs
weight: 2210
url: /el/net/aspose.threed.render/pixelformat/
---
## PixelFormat enumeration

Η μορφή του pixel που χρησιμοποιείται στη μονάδα υφής.

```csharp
public enum PixelFormat
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Unknown | `0` | Άγνωστη μορφή pixel. |
| L8 | `1` | 8-bit μορφή pixel, όλα τα bits φωτεινότητας. |
| L16 | `2` | 16-bit μορφή pixel, όλα τα bits φωτεινότητας. |
| A8 | `3` | 8-bit μορφή pixel, όλα τα bits αλφα. |
| A4L4 | `4` | 8-bit μορφή pixel, 4 bits αλφα, 4 bits φωτεινότητα. |
| BYTE_LA | `5` | 2 byte μορφή pixel, 1 byte φωτεινότητα, 1 byte αλφα |
| R5G6B5 | `6` | 16-bit μορφή pixel, 5 bits κόκκινο, 6 bits πράσινο, 5 bits μπλε. |
| B5G6R5 | `7` | 16-bit μορφή pixel, 5 bits κόκκινο, 6 bits πράσινο, 5 bits μπλε. |
| R3G3B2 | `8` | 8-bit μορφή pixel, 2 bits μπλε, 3 bits πράσινο, 3 bits κόκκινο. |
| A4R4G4B4 | `9` | 16-bit μορφή pixel, 4 bits για αλφα, κόκκινο, πράσινο και μπλε. |
| A1R5G5B5 | `10` | 16-bit μορφή pixel, 5 bits για μπλε, πράσινο, κόκκινο και 1 για αλφα. |
| R8G8B8 | `11` | 24-bit μορφή pixel, 8 bits για κόκκινο, πράσινο και μπλε. |
| B8G8R8 | `12` | 24-bit μορφή pixel, 8 bits για μπλε, πράσινο και κόκκινο. |
| A8R8G8B8 | `13` | 32-bit μορφή pixel, 8 bits για αλφα, κόκκινο, πράσινο και μπλε. |
| A8B8G8R8 | `14` | 32-bit μορφή pixel, 8 bits για μπλε, πράσινο, κόκκινο και αλφα. |
| B8G8R8A8 | `15` | 32-bit μορφή pixel, 8 bits για μπλε, πράσινο, κόκκινο και αλφα. |
| R8G8B8A8 | `16` | 32-bit μορφή pixel, 8 bits για κόκκινο, πράσινο, μπλε και αλφα. |
| X8R8G8B8 | `17` | 32-bit μορφή pixel, 8 bits για κόκκινο, 8 bits για πράσινο, 8 bits για μπλε όπως A8R8G8B8, αλλά το αλφα θα απορριφθεί. |
| X8B8G8R8 | `18` | 32-bit μορφή pixel, 8 bits για μπλε, 8 bits για πράσινο, 8 bits για κόκκινο όπως A8B8G8R8, αλλά το αλφα θα απορριφθεί. |
| A2R10G10B10 | `19` | 32-bit μορφή pixel, 2 bits για αλφα, 10 bits για κόκκινο, πράσινο και μπλε. |
| A2B10G10R10 | `20` | 32-bit μορφή pixel, 10 bits για μπλε, πράσινο και κόκκινο, 2 bits για αλφα. |
| DXT1 | `21` | DDS (DirectDraw Surface) μορφή DXT1. |
| DXT2 | `22` | DDS (DirectDraw Surface) μορφή DXT2. |
| DXT3 | `23` | DDS (DirectDraw Surface) μορφή DXT3. |
| DXT4 | `24` | DDS (DirectDraw Surface) μορφή DXT4. |
| DXT5 | `25` | DDS (DirectDraw Surface) μορφή DXT5. |
| FLOAT16_R | `26` | 16-bit μορφή pixel, 16 bits (float) για κόκκινο |
| FLOAT16_RGB | `27` | 48-bit μορφή pixel, 16 bits (float) για κόκκινο, 16 bits (float) για πράσινο, 16 bits (float) για μπλε |
| FLOAT16_RGBA | `28` | 64-bit μορφή pixel, 16 bits (float) για κόκκινο, 16 bits (float) για πράσινο, 16 bits (float) για μπλε, 16 bits (float) για αλφα |
| FLOAT32_R | `29` | 32-bit μορφή pixel, 32 bits (float) για κόκκινο |
| FLOAT32_RGB | `30` | μορφή pixel 96-bit, 32 bit (float) για το κόκκινο, 32 bit (float) για το πράσινο, 32 bit (float) για το μπλε |
| FLOAT32_RGBA | `31` | μορφή pixel 128-bit, 32 bit (float) για το κόκκινο, 32 bit (float) για το πράσινο, 32 bit (float) για το μπλε, 32 bit (float) για το άλφα |
| FLOAT16_GR | `32` | μορφή pixel 32-bit, 2-κανάλι s10e5 floating point, 16-bit πράσινο, 16-bit κόκκινο |
| FLOAT32_GR | `33` | μορφή pixel 64-bit, 2-κανάλι floating point, 32-bit πράσινο, 32-bit κόκκινο |
| DEPTH | `34` | μορφή υφής βάθους. |
| SHORT_RGBA | `35` | μορφή pixel 64-bit, 16 bit για το κόκκινο, πράσινο, μπλε και άλφα |
| SHORT_GR | `36` | μορφή pixel 32-bit, 16-bit πράσινο, 16-bit κόκκινο |
| SHORT_RGB | `37` | μορφή pixel 48-bit, 16 bit για το κόκκινο, πράσινο και μπλε |
| R32_UINT | `38` | μορφή pixel 32-bit, 32 bit κόκκινο (unsigned int). |
| R32G32_UINT | `39` | μορφή pixel 64-bit, 32 bit κόκκινο (unsigned int), 32 bit μπλε (unsigned int). |
| R32G32B32A32_UINT | `40` | μορφή pixel 128-bit, 32 bit κόκκινο (unsigned int), 32 bit μπλε (unsigned int), 32 bit πράσινο (unsigned int), 32 bit άλφα (unsigned int). |
| R8 | `41` | μορφή pixel 8-bit, όλα τα bit κόκκινο. |
| G8 | `42` | μορφή pixel 8-bit, όλα τα bit πράσινο. |
| B8 | `43` | μορφή pixel 8-bit, όλα τα bit μπλε. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


