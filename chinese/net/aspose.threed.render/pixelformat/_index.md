---
title: PixelFormat
second_title: Aspose.3D for .NET API 参考
description: 纹理单元中使用的像素格式
type: docs
weight: 1980
url: /zh/net/aspose.threed.render/pixelformat/
---
## PixelFormat enumeration

纹理单元中使用的像素格式。

```csharp
public enum PixelFormat
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Unknown | `0` | 未知像素格式。 |
| L8 | `1` | 8 位像素格式，所有位亮度。 |
| L16 | `2` | 16 位像素格式，所有位亮度。 |
| A8 | `3` | 8 位像素格式，所有位 alpha。 |
| A4L4 | `4` | 8 位像素格式，4 位 alpha，4 位亮度。 |
| BYTE_LA | `5` | 2 字节像素格式，1 字节亮度，1 字节 alpha |
| R5G6B5 | `6` | 16 位像素格式，5 位红色，6 位绿色，5 位蓝色。 |
| B5G6R5 | `7` | 16 位像素格式，5 位红色，6 位绿色，5 位蓝色。 |
| R3G3B2 | `8` | 8 位像素格式，2 位蓝色，3 位绿色，3 位红色。 |
| A4R4G4B4 | `9` | 16 位像素格式，4 位用于 alpha、红色、绿色和蓝色。 |
| A1R5G5B5 | `10` | 16 位像素格式，5 位用于蓝色、绿色、红色和 1 位用于 alpha。 |
| R8G8B8 | `11` | 24 位像素格式，红色、绿色和蓝色 8 位。 |
| B8G8R8 | `12` | 24 位像素格式，蓝色、绿色和红色 8 位。 |
| A8R8G8B8 | `13` | 32 位像素格式，8 位用于 alpha、红色、绿色和蓝色。 |
| A8B8G8R8 | `14` | 32 位像素格式，8 位用于蓝色、绿色、红色和 alpha。 |
| B8G8R8A8 | `15` | 32 位像素格式，8 位用于蓝色、绿色、红色和 alpha。 |
| R8G8B8A8 | `16` | 32 位像素格式，红色、绿色、蓝色和 alpha 为 8 位。 |
| X8R8G8B8 | `17` | 32 位像素格式，红色 8 位，绿色 8 位，蓝色 8 位，如 A8R8G8B8，但 alpha 将被丢弃 |
| X8B8G8R8 | `18` | 32 位像素格式，蓝色 8 位，绿色 8 位，红色 8 位，如 A8B8G8R8，但 alpha 将被丢弃 |
| A2R10G10B10 | `19` | 32 位像素格式，2 位用于 alpha，10 位用于红色、绿色和蓝色。 |
| A2B10G10R10 | `20` | 32 位像素格式，10 位用于蓝色、绿色和红色，2 位用于 alpha。 |
| DXT1 | `21` | DDS（DirectDraw 表面）DXT1 格式。 |
| DXT2 | `22` | DDS（DirectDraw 表面）DXT2 格式。 |
| DXT3 | `23` | DDS（DirectDraw 表面）DXT3 格式。 |
| DXT4 | `24` | DDS（DirectDraw 表面）DXT4 格式。 |
| DXT5 | `25` | DDS（DirectDraw 表面）DXT5 格式。 |
| FLOAT16_R | `26` | 16 位像素格式，红色为 16 位（浮点数） |
| FLOAT16_RGB | `27` | 48 位像素格式，红色为 16 位（浮点），绿色为 16 位（浮点），蓝色为 16 位（浮点） |
| FLOAT16_RGBA | `28` | 64 位像素格式，红色为 16 位（浮点数），绿色为 16 位（浮点数），蓝色为 16 位（浮点数），alpha 为 16 位（浮点数） |
| FLOAT32_R | `29` | 32 位像素格式，红色为 32 位（浮点数） |
| FLOAT32_RGB | `30` | 96 位像素格式，红色 32 位（浮点），绿色 32 位（浮点），蓝色 32 位（浮点） |
| FLOAT32_RGBA | `31` | 128 位像素格式，红色为 32 位（浮点），绿色为 32 位（浮点），蓝色为 32 位（浮点），alpha 为 32 位（浮点） |
| FLOAT16_GR | `32` | 32 位，2 通道 s10e5 浮点像素格式，16 位绿色，16 位红色 |
| FLOAT32_GR | `33` | 64 位，2 通道浮点像素格式，32 位绿色，32 位红色 |
| DEPTH | `34` | 深度纹理格式。 |
| SHORT_RGBA | `35` | 64 位像素格式，红色、绿色、蓝色和 alpha 为 16 位 |
| SHORT_GR | `36` | 32 位像素格式，16 位绿色，16 位红色 |
| SHORT_RGB | `37` | 48 位像素格式，16 位红色、绿色和蓝色 |
| R32_UINT | `38` | 32 位像素格式，32 位红色（无符号整数）。 |
| R32G32_UINT | `39` | 64 位像素格式，32 位红色（无符号整数），32 位蓝色（无符号整数）。 |
| R32G32B32A32_UINT | `40` | 128 位像素格式，32 位红色（无符号整数），32 位蓝色（无符号整数），32 位绿色（无符号整数），32 位阿尔法（无符号整数）。 |
| R8 | `41` | 8 位像素格式，所有位为红色。 |

### 也可以看看

* 命名空间 [Aspose.ThreeD.Render](../../aspose.threed.render)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->