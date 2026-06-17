---
title: "Watermark"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Bir ağ üzerinden kör filigranı kodlamak/çözmek için araç.  @hideconstructor


## Yöntemler

### encodeWatermark{#encodeWatermark}

| Ad | Açıklama |
| --- | --- |
| encodeWatermark(input, text) | Metni ağın kör filigranına kodlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| input | Mesh | Kör bir filigranı kodlamak için ağ |
| text | String | Ağa kodlamak için metin |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Ad | Açıklama |
| --- | --- |
| encodeWatermark(input, text, password) | Metni ağın kör filigranına kodlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| input | Mesh | Kör bir filigranı kodlamak için ağ |
| text | String | Ağa kodlamak için metin |
| password | String | Filigranı korumak için şifre, isteğe bağlıdır |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Ad | Açıklama |
| --- | --- |
| decodeWatermark(input) | Filigranı bir ağdan çözer |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| input | Mesh | Filigranı çıkarmak için ağ |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Ad | Açıklama |
| --- | --- |
| decodeWatermark(input, password) | Filigranı bir ağdan çözer |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| input | Mesh | Filigranı çıkarmak için ağ |
| password | String | Filigranı çözmek için şifre |

 **Result:**
String


---



