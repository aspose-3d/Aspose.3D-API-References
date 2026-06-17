---
title: "DracoFormat"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco 형식  @hideconstructor


## 메서드

### getVersion{#getVersion}

| 이름 | 설명 |
| --- | --- |
| getVersion() | 파일 형식 버전을 가져옵니다 |

 **Result:**



---


### getExtension{#getExtension}

| 이름 | 설명 |
| --- | --- |
| getExtension() | 이 유형의 확장자 이름을 가져옵니다. |

 **Result:**



---


### getExtensions{#getExtensions}

| 이름 | 설명 |
| --- | --- |
| getExtensions() | 이 유형의 확장자 이름들을 가져옵니다. |

 **Result:**



---


### getContentType{#getContentType}

| 이름 | 설명 |
| --- | --- |
| getContentType() | 파일 형식 콘텐츠 유형을 가져옵니다. 속성 값은 FileContentType 정수 상수입니다. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| 이름 | 설명 |
| --- | --- |
| getFileFormatType() | 파일 형식 유형을 가져옵니다 |

 **Result:**



---


### decode{#decode}

| 이름 | 설명 |
| --- | --- |
| decode(fileName) | 지정된 파일 이름에서 포인트 클라우드 또는 메쉬를 디코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 파일 이름에는 drc 파일이 포함됩니다. |

 **Result:**
Geometry


---


### decode{#decode}

| 이름 | 설명 |
| --- | --- |
| decode(data) | 메모리 데이터에서 포인트 클라우드 또는 메쉬를 디코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| data | byte[] | 원시 drc 바이트 |

 **Result:**
Geometry


---


### encode{#encode}

| 이름 | 설명 |
| --- | --- |
| encode(entity, fileName, options) | 엔티티를 지정된 파일에 인코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| entity | Entity | 인코딩될 엔티티 |
| fileName | String | 작성될 파일 이름 |
| 옵션 | DracoSaveOptions | 포인트 클라우드 인코딩을 위한 추가 옵션 |

 **Result:**
Geometry


---


### encode{#encode}

| 이름 | 설명 |
| --- | --- |
| encode(entity, options) | 엔티티를 Draco 원시 데이터로 인코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| entity | Entity | 인코딩될 엔티티 |
| 옵션 | DracoSaveOptions | 포인트 클라우드 인코딩을 위한 추가 옵션 |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| 이름 | 설명 |
| --- | --- |
| createLoadOptions() | 이 파일 형식에 대한 기본 로드 옵션을 생성합니다. |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| 이름 | 설명 |
| --- | --- |
| createSaveOptions() | 이 파일 형식에 대한 기본 저장 옵션을 생성합니다. |

 **Result:**
SaveOptions


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 형식을 문자열로 변환 |

 **Result:**
String


---



