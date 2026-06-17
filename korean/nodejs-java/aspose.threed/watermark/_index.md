---
title: "Watermark"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/watermark/
---
## Watermark class

메시에서 블라인드 워터마크를 인코딩/디코딩하기 위한 유틸리티.  @hideconstructor


## 메서드

### encodeWatermark{#encodeWatermark}

| 이름 | 설명 |
| --- | --- |
| encodeWatermark(input, text) | 텍스트를 메쉬의 블라인드 워터마크로 인코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| input | Mesh | 블라인드 워터마크를 인코딩할 메쉬 |
| text | String | 메쉬에 인코딩할 텍스트 |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| 이름 | 설명 |
| --- | --- |
| encodeWatermark(input, text, password) | 텍스트를 메쉬의 블라인드 워터마크로 인코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| input | Mesh | 블라인드 워터마크를 인코딩할 메쉬 |
| text | String | 메쉬에 인코딩할 텍스트 |
| password | String | 워터마크를 보호하기 위한 비밀번호이며, 선택 사항입니다. |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| 이름 | 설명 |
| --- | --- |
| decodeWatermark(input) | 메쉬에서 워터마크를 디코드합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| input | Mesh | 워터마크를 추출할 메쉬 |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| 이름 | 설명 |
| --- | --- |
| decodeWatermark(input, password) | 메쉬에서 워터마크를 디코드합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| input | Mesh | 워터마크를 추출할 메쉬 |
| password | String | 워터마크를 복호화하기 위한 비밀번호 |

 **Result:**
String


---



