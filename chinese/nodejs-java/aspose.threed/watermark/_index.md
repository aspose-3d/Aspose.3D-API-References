---
title: "Watermark"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/watermark/
---
## Watermark class

用于对盲水印进行编码/解码到/从网格的实用工具。  @hideconstructor


## 方法

### encodeWatermark{#encodeWatermark}

| 名称 | 描述 |
| --- | --- |
| encodeWatermark(input, text) | 将文本编码为网格的盲水印。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| input | Mesh | 用于编码盲水印的网格 |
| text | 字符串 | 要编码到网格的文本 |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| 名称 | 描述 |
| --- | --- |
| encodeWatermark(input, text, password) | 将文本编码为网格的盲水印。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| input | Mesh | 用于编码盲水印的网格 |
| text | 字符串 | 要编码到网格的文本 |
| password | 字符串 | 用于保护水印的密码，可选。 |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| 名称 | 描述 |
| --- | --- |
| decodeWatermark(input) | 从网格中解码水印 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| input | Mesh | 用于提取水印的网格 |

 **Result:**
字符串


---


### decodeWatermark{#decodeWatermark}

| 名称 | 描述 |
| --- | --- |
| decodeWatermark(input, password) | 从网格中解码水印 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| input | Mesh | 用于提取水印的网格 |
| password | 字符串 | 用于解密水印的密码 |

 **Result:**
字符串


---



