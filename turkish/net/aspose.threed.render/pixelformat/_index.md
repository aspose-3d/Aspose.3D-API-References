---
title: PixelFormat
second_title: Aspose.3D for .NET API Referansı
description: Doku biriminde kullanılan piksel biçimi.
type: docs
weight: 1990
url: /tr/net/aspose.threed.render/pixelformat/
---
## PixelFormat enumeration

Doku biriminde kullanılan piksel biçimi.

```csharp
public enum PixelFormat
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Unknown | `0` | Bilinmeyen piksel biçimi. |
| L8 | `1` | 8 bit piksel biçimi, tüm bitler parlaklık. |
| L16 | `2` | 16 bit piksel biçimi, tüm bitler parlaklık. |
| A8 | `3` | 8 bit piksel biçimi, tüm bitler alfa. |
| A4L4 | `4` | 8 bit piksel biçimi, 4 bit alfa, 4 bit parlaklık. |
| BYTE_LA | `5` | 2 bayt piksel biçimi, 1 bayt parlaklık, 1 bayt alpha |
| R5G6B5 | `6` | 16 bit piksel formatı, 5 bit kırmızı, 6 bit yeşil, 5 bit mavi. |
| B5G6R5 | `7` | 16 bit piksel formatı, 5 bit kırmızı, 6 bit yeşil, 5 bit mavi. |
| R3G3B2 | `8` | 8 bit piksel formatı, 2 bit mavi, 3 bit yeşil, 3 bit kırmızı. |
| A4R4G4B4 | `9` | 16 bit piksel formatı, alfa, kırmızı, yeşil ve mavi için 4 bit. |
| A1R5G5B5 | `10` | 16 bit piksel formatı, mavi, yeşil, kırmızı için 5 bit ve alfa için 1 bit. |
| R8G8B8 | `11` | 24 bit piksel formatı, kırmızı, yeşil ve mavi için 8 bit. |
| B8G8R8 | `12` | 24 bit piksel formatı, mavi, yeşil ve kırmızı için 8 bit. |
| A8R8G8B8 | `13` | 32 bit piksel formatı, alfa, kırmızı, yeşil ve mavi için 8 bit. |
| A8B8G8R8 | `14` | 32 bit piksel formatı, mavi, yeşil, kırmızı ve alfa için 8 bit. |
| B8G8R8A8 | `15` | 32 bit piksel formatı, mavi, yeşil, kırmızı ve alfa için 8 bit. |
| R8G8B8A8 | `16` | 32 bit piksel formatı, kırmızı, yeşil, mavi ve alfa için 8 bit. |
| X8R8G8B8 | `17` | 32 bit piksel biçimi, kırmızı için 8 bit, yeşil için 8 bit, A8R8G8B8 gibi mavi için 8 bit, ancak alfa atılır |
| X8B8G8R8 | `18` | 32 bit piksel biçimi, mavi için 8 bit, yeşil için 8 bit, A8B8G8R8 gibi kırmızı için 8 bit, ancak alfa atılacak |
| A2R10G10B10 | `19` | 32 bit piksel formatı, alfa için 2 bit, kırmızı, yeşil ve mavi için 10 bit. |
| A2B10G10R10 | `20` | 32 bit piksel formatı, mavi, yeşil ve kırmızı için 10 bit, alfa için 2 bit. |
| DXT1 | `21` | DDS (DirectDraw Yüzeyi) DXT1 formatı. |
| DXT2 | `22` | DDS (DirectDraw Yüzeyi) DXT2 formatı. |
| DXT3 | `23` | DDS (DirectDraw Yüzeyi) DXT3 formatı. |
| DXT4 | `24` | DDS (DirectDraw Yüzeyi) DXT4 formatı. |
| DXT5 | `25` | DDS (DirectDraw Yüzeyi) DXT5 formatı. |
| FLOAT16_R | `26` | 16 bit piksel formatı, kırmızı için 16 bit (kayan) |
| FLOAT16_RGB | `27` | 48 bit piksel formatı, kırmızı için 16 bit (kayan), yeşil için 16 bit (kayan), mavi için 16 bit (kayan) |
| FLOAT16_RGBA | `28` | 64 bit piksel formatı, kırmızı için 16 bit (kayan), yeşil için 16 bit (kayan), mavi için 16 bit (kayan), alfa için 16 bit (kayan) |
| FLOAT32_R | `29` | 32 bit piksel formatı, kırmızı için 32 bit (kayan) |
| FLOAT32_RGB | `30` | 96 bit piksel formatı, kırmızı için 32 bit (kayan), yeşil için 32 bit (kayan), mavi için 32 bit (kayan) |
| FLOAT32_RGBA | `31` | 128 bit piksel formatı, kırmızı için 32 bit (kayan), yeşil için 32 bit (kayan), mavi için 32 bit (kayan), alfa için 32 bit (kayan) |
| FLOAT16_GR | `32` | 32 bit, 2 kanallı s10e5 kayan nokta piksel formatı, 16 bit yeşil, 16 bit kırmızı |
| FLOAT32_GR | `33` | 64 bit, 2 kanallı kayan nokta piksel formatı, 32 bit yeşil, 32 bit kırmızı |
| DEPTH | `34` | Derinlik doku formatı. |
| SHORT_RGBA | `35` | 64 bit piksel formatı, kırmızı, yeşil, mavi ve alfa için 16 bit |
| SHORT_GR | `36` | 32 bit piksel formatı, 16 bit yeşil, 16 bit kırmızı |
| SHORT_RGB | `37` | 48 bit piksel formatı, kırmızı, yeşil ve mavi için 16 bit |
| R32_UINT | `38` | 32 bit piksel biçimi, 32 bit kırmızı (işaretsiz int). |
| R32G32_UINT | `39` | 64 bit piksel formatı, 32 bit kırmızı (işaretsiz int), 32 bit mavi (işaretsiz int). |
| R32G32B32A32_UINT | `40` | 128 bit piksel formatı, 32 bit kırmızı (işaretsiz int), 32 bit mavi (işaretsiz int), 32 bit yeşil (işaretsiz int), 32 bit alfa (işaretsiz int). |
| R8 | `41` | 8 bit piksel formatı, tüm bitler kırmızı. |

### Ayrıca bakınız

* ad alanı [Aspose.ThreeD.Render](../../aspose.threed.render)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
