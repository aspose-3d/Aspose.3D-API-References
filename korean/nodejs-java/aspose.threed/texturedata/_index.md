---
title: "TextureData"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

이 클래스는 텍스처의 원시 데이터와 포맷 정의를 포함합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | TextureData의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 너비 | 숫자 | null |
| 높이 | 숫자 | null |
| strid | 숫자 | null |
| bytesPerPixe | 숫자 | null |
| pixelFormat | PixelFormat | PixelFormat |
| 데이터 | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | 새로운 TextureData를 생성하고 픽셀 데이터를 할당합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 너비 | 숫자 | null |
| 높이 | 숫자 | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2() | TextureData의 생성자 |

 **Result:**



---


### getData{#getData}

| 이름 | 설명 |
| --- | --- |
| getData() | 픽셀 데이터의 원시 바이트 |

 **Result:**



---


### getWidth{#getWidth}

| 이름 | 설명 |
| --- | --- |
| getWidth() | 수평 픽셀 수 |

 **Result:**



---


### getHeight{#getHeight}

| 이름 | 설명 |
| --- | --- |
| getHeight() | 수직 픽셀 수 |

 **Result:**



---


### getStride{#getStride}

| 이름 | 설명 |
| --- | --- |
| getStride() | 스캔라인의 바이트 수. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| 이름 | 설명 |
| --- | --- |
| getBytesPerPixel() | 픽셀당 바이트 수 |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| 이름 | 설명 |
| --- | --- |
| getPixelFormat() | 픽셀 형식입니다. 이 속성의 값은 PixelFormat 정수 상수입니다. |

 **Result:**



---


### fromFile{#fromFile}

| 이름 | 설명 |
| --- | --- |
| fromFile(fileName) | 파일에서 텍스처를 로드합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| 이름 | 설명 |
| --- | --- |
| save(fileName) | 텍스처 데이터를 이미지 파일에 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 이미지가 저장될 파일 이름입니다. |

 **Result:**
TextureData


---


### save{#save}

| 이름 | 설명 |
| --- | --- |
| save(fileName, format) | 텍스처 데이터를 이미지 파일에 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 이미지가 저장될 파일 이름입니다. |
| format | String | 출력 파일의 이미지 포맷입니다. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| 이름 | 설명 |
| --- | --- |
| mapPixels(mapMode) | 읽기/쓰기를 위해 모든 픽셀을 매핑합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| 이름 | 설명 |
| --- | --- |
| mapPixels(mapMode, format) | 주어진 픽셀 포맷으로 읽기/쓰기를 위해 모든 픽셀을 매핑합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| 이름 | 설명 |
| --- | --- |
| mapPixels(rect, mapMode, format) | rect 로 지정된 픽셀을 주어진 픽셀 포맷으로 읽기/쓰기를 위해 매핑합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rect | 액세스할 픽셀 영역 |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| 이름 | 설명 |
| --- | --- |
| transformPixelFormat(pixelFormat) | 픽셀의 레이아웃을 새로운 픽셀 포맷으로 변환합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



