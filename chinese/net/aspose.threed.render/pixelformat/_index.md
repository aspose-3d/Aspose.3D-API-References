---
title: "枚举 PixelFormat"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.PixelFormat 枚举。纹理单元中使用的像素格式"
type: docs
weight: 2210
url: /zh/net/aspose.threed.render/pixelformat/
---
## PixelFormat enumeration

纹理单元中使用的像素格式。

```csharp
public enum PixelFormat
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Unknown | `0` | 未知像素格式。 |
| L8 | `1` | 8位像素格式，所有位为亮度。 |
| L16 | `2` | 16位像素格式，所有位为亮度。 |
| A8 | `3` | 8位像素格式，所有位为透明度。 |
| A4L4 | `4` | 8位像素格式，4位透明度，4位亮度。 |
| BYTE_LA | `5` | 2字节像素格式，1字节亮度，1字节透明度 |
| R5G6B5 | `6` | 16位像素格式，5位红色，6位绿色，5位蓝色。 |
| B5G6R5 | `7` | 16位像素格式，5位红色，6位绿色，5位蓝色。 |
| R3G3B2 | `8` | 8位像素格式，2位蓝色，3位绿色，3位红色。 |
| A4R4G4B4 | `9` | 16位像素格式，4位用于透明度、红色、绿色和蓝色。 |
| A1R5G5B5 | `10` | 16位像素格式，5位用于蓝色、绿色、红色，1位用于透明度。 |
| R8G8B8 | `11` | 24位像素格式，8位用于红色、绿色和蓝色。 |
| B8G8R8 | `12` | 24位像素格式，8位用于蓝色、绿色和红色。 |
| A8R8G8B8 | `13` | 32位像素格式，8位用于透明度、红色、绿色和蓝色。 |
| A8B8G8R8 | `14` | 32位像素格式，8位用于蓝色、绿色、红色和透明度。 |
| B8G8R8A8 | `15` | 32位像素格式，8位用于蓝色、绿色、红色和透明度。 |
| R8G8B8A8 | `16` | 32位像素格式，8位用于红色、绿色、蓝色和透明度。 |
| X8R8G8B8 | `17` | 32位像素格式，红色8位，绿色8位，蓝色8位，如 A8R8G8B8，但透明度将被丢弃 |
| X8B8G8R8 | `18` | 32位像素格式，蓝色8位，绿色8位，红色8位，如 A8B8G8R8，但透明度将被丢弃 |
| A2R10G10B10 | `19` | 32位像素格式，2位用于透明度，10位用于红色、绿色和蓝色。 |
| A2B10G10R10 | `20` | 32位像素格式，10位用于蓝色、绿色和红色，2位用于透明度。 |
| DXT1 | `21` | DDS（DirectDraw Surface）DXT1 格式。 |
| DXT2 | `22` | DDS（DirectDraw Surface）DXT2 格式。 |
| DXT3 | `23` | DDS（DirectDraw Surface）DXT3 格式。 |
| DXT4 | `24` | DDS（DirectDraw Surface）DXT4 格式。 |
| DXT5 | `25` | DDS（DirectDraw Surface）DXT5 格式。 |
| FLOAT16_R | `26` | 16位像素格式，红色 16 位（浮点）。 |
| FLOAT16_RGB | `27` | 48位像素格式，红色 16 位（浮点），绿色 16 位（浮点），蓝色 16 位（浮点） |
| FLOAT16_RGBA | `28` | 64 位像素格式，红色使用 16 位 (float)，绿色使用 16 位 (float)，蓝色使用 16 位 (float)，透明度使用 16 位 (float) |
| FLOAT32_R | `29` | 32 位像素格式，红色使用 32 位 (float) |
| FLOAT32_RGB | `30` | 96 位像素格式，红色使用 32 位 (float)，绿色使用 32 位 (float)，蓝色使用 32 位 (float) |
| FLOAT32_RGBA | `31` | 128 位像素格式，红色使用 32 位 (float)，绿色使用 32 位 (float)，蓝色使用 32 位 (float)，透明度使用 32 位 (float) |
| FLOAT16_GR | `32` | 32 位，2 通道 s10e5 浮点像素格式，绿色使用 16 位，红色使用 16 位 |
| FLOAT32_GR | `33` | 64 位，2 通道浮点像素格式，绿色使用 32 位，红色使用 32 位 |
| DEPTH | `34` | 深度纹理格式。 |
| SHORT_RGBA | `35` | 64 位像素格式，红、绿、蓝和透明度各使用 16 位 |
| SHORT_GR | `36` | 32 位像素格式，绿色使用 16 位，红色使用 16 位 |
| SHORT_RGB | `37` | 48 位像素格式，红、绿、蓝各使用 16 位 |
| R32_UINT | `38` | 32 位像素格式，红色使用 32 位 (unsigned int)。 |
| R32G32_UINT | `39` | 64 位像素格式，红色使用 32 位 (unsigned int)，蓝色使用 32 位 (unsigned int)。 |
| R32G32B32A32_UINT | `40` | 128 位像素格式，红色使用 32 位 (unsigned int)，蓝色使用 32 位 (unsigned int)，绿色使用 32 位 (unsigned int)，透明度使用 32 位 (unsigned int)。 |
| R8 | `41` | 8 位像素格式，全部位用于红色。 |
| G8 | `42` | 8 位像素格式，全部位用于绿色。 |
| B8 | `43` | 8 位像素格式，全部位用于蓝色。 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


