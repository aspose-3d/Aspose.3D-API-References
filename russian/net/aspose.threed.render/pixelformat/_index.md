---
title: PixelFormat
second_title: Справочник по Aspose.3D для .NET API
description: Формат пикселя используемый в текстурном блоке.
type: docs
weight: 1980
url: /ru/net/aspose.threed.render/pixelformat/
---
## PixelFormat enumeration

Формат пикселя, используемый в текстурном блоке.

```csharp
public enum PixelFormat
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Unknown | `0` | Неизвестный формат пикселей. |
| L8 | `1` | 8-битный формат пикселей, все биты яркости. |
| L16 | `2` | 16-битный формат пикселей, все биты яркости. |
| A8 | `3` | 8-битный формат пикселей, все биты альфа. |
| A4L4 | `4` | 8-битный формат пикселей, 4 бита альфа, 4 бита яркости. |
| BYTE_LA | `5` | 2-байтовый формат пикселей, 1 байт яркости, 1 байт альфа-канала |
| R5G6B5 | `6` | 16-битный формат пикселей, 5 бит красного цвета, 6 бит зеленого цвета, 5 бит синего цвета. |
| B5G6R5 | `7` | 16-битный формат пикселей, 5 бит красного цвета, 6 бит зеленого цвета, 5 бит синего цвета. |
| R3G3B2 | `8` | 8-битный формат пикселей, 2 бита синего, 3 бита зеленого, 3 бита красного. |
| A4R4G4B4 | `9` | 16-битный формат пикселей, 4 бита для альфа, красного, зеленого и синего. |
| A1R5G5B5 | `10` | 16-битный формат пикселей, 5 бит для синего, зеленого, красного и 1 для альфа-канала. |
| R8G8B8 | `11` | 24-битный формат пикселей, 8 бит для красного, зеленого и синего. |
| B8G8R8 | `12` | 24-битный формат пикселей, 8 бит для синего, зеленого и красного. |
| A8R8G8B8 | `13` | 32-битный формат пикселей, 8 бит для альфа, красного, зеленого и синего. |
| A8B8G8R8 | `14` | 32-битный формат пикселей, 8 бит для синего, зеленого, красного и альфа-канала. |
| B8G8R8A8 | `15` | 32-битный формат пикселей, 8 бит для синего, зеленого, красного и альфа-канала. |
| R8G8B8A8 | `16` | 32-битный формат пикселей, 8 бит для красного, зеленого, синего и альфа-канала. |
| X8R8G8B8 | `17` | 32-битный формат пикселей, 8 бит для красного, 8 бит для зеленого, 8 бит для синего, как A8R8G8B8, но альфа-канал будет отброшен |
| X8B8G8R8 | `18` | 32-битный формат пикселей, 8 бит для синего, 8 бит для зеленого, 8 бит для красного, как A8B8G8R8, но альфа-канал будет отброшен |
| A2R10G10B10 | `19` | 32-битный формат пикселей, 2 бита для альфа-канала, 10 бит для красного, зеленого и синего. |
| A2B10G10R10 | `20` | 32-битный формат пикселей, 10 бит для синего, зеленого и красного, 2 бита для альфа-канала. |
| DXT1 | `21` | Формат DDS (поверхность DirectDraw) DXT1. |
| DXT2 | `22` | Формат DDS (поверхность DirectDraw) DXT2. |
| DXT3 | `23` | Формат DDS (поверхность DirectDraw) DXT3. |
| DXT4 | `24` | Формат DDS (поверхность DirectDraw) DXT4. |
| DXT5 | `25` | Формат DDS (поверхность DirectDraw) DXT5. |
| FLOAT16_R | `26` | 16-битный формат пикселей, 16 бит (с плавающей запятой) для красного цвета |
| FLOAT16_RGB | `27` | 48-битный формат пикселей, 16 бит (с плавающей запятой) для красного цвета, 16 бит (с плавающей запятой) для зеленого, 16 бит (с плавающей запятой) для синего |
| FLOAT16_RGBA | `28` | 64-битный формат пикселей, 16 бит (с плавающей запятой) для красного, 16 бит (с плавающей запятой) для зеленого, 16 бит (с плавающей запятой) для синего, 16 бит (с плавающей запятой) для альфа-канала |
| FLOAT32_R | `29` | 32-битный формат пикселей, 32 бита (с плавающей запятой) для красного цвета |
| FLOAT32_RGB | `30` | 96-битный формат пикселей, 32 бита (с плавающей запятой) для красного, 32 бита (с плавающей запятой) для зеленого, 32 бита (с плавающей запятой) для синего |
| FLOAT32_RGBA | `31` | 128-битный формат пикселей, 32 бита (с плавающей запятой) для красного, 32 бита (с плавающей запятой) для зеленого, 32 бита (с плавающей запятой) для синего, 32 бита (с плавающей запятой) для альфа-канала |
| FLOAT16_GR | `32` | 32-битный, 2-канальный формат пикселей с плавающей запятой s10e5, 16-битный зеленый, 16-битный красный |
| FLOAT32_GR | `33` | 64-битный, 2-канальный формат пикселей с плавающей запятой, 32-битный зеленый, 32-битный красный |
| DEPTH | `34` | Формат текстуры глубины. |
| SHORT_RGBA | `35` | 64-битный формат пикселей, 16 бит для красного, зеленого, синего и альфа-канала |
| SHORT_GR | `36` | 32-битный формат пикселей, 16-битный зеленый, 16-битный красный |
| SHORT_RGB | `37` | 48-битный формат пикселей, 16 бит для красного, зеленого и синего |
| R32_UINT | `38` | 32-битный формат пикселей, 32 бита красного цвета (целое без знака). |
| R32G32_UINT | `39` | 64-битный формат пикселей, 32 бита красного (целое без знака), 32 бита синего (целое без знака). |
| R32G32B32A32_UINT | `40` | 128-битный формат пикселей, 32 бита красного (целое без знака), 32 бита синего (целое без знака), 32 бита зеленого (целое без знака), 32 бита альфа (целое без знака). |
| R8 | `41` | 8-битный формат пикселей, все биты красные. |

### Смотрите также

* пространство имен [Aspose.ThreeD.Render](../../aspose.threed.render)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->