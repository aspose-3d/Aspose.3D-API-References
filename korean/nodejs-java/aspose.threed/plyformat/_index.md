---
title: "PlyFormat"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

PLY 형식.  @hideconstructor


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


### encode{#encode}

| 이름 | 설명 |
| --- | --- |
| encode(entity, fileName) | 엔티티를 인코딩하고 결과를 외부 파일에 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| entity | Entity | 인코딩할 엔티티 |
| fileName | String | 작성할 파일 |

 **Result:**



---


### encode{#encode}

| 이름 | 설명 |
| --- | --- |
| encode(entity, fileName, opt) | 엔티티를 인코딩하고 결과를 외부 파일에 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| entity | Entity | 인코딩할 엔티티 |
| fileName | String | 작성할 파일 |
| opt | PlySaveOptions | 저장 옵션 |

 **Result:**



---


### decode{#decode}

| 이름 | 설명 |
| --- | --- |
| decode(fileName) | 지정된 스트림에서 포인트 클라우드 또는 메쉬를 디코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 입력 스트림 |

 **Result:**
Geometry


---


### decode{#decode}

| 이름 | 설명 |
| --- | --- |
| decode(fileName, opt) | 지정된 스트림에서 포인트 클라우드 또는 메쉬를 디코딩합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 입력 스트림 |
| opt | PlyLoadOptions | PLY 형식의 로드 옵션 |

 **Result:**
Geometry


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



