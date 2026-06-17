---
title: "PdfFormat"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Adobe의 Portable Document Format  @hideconstructor


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


### extract{#extract}

| 이름 | 설명 |
| --- | --- |
| extract(fileName, password) | PDF 파일에서 원시 3D 콘텐츠를 추출합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |
| 비밀번호 | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| 이름 | 설명 |
| --- | --- |
| extractScene(fileName) | PDF 파일에서 3D 씬을 추출합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| 이름 | 설명 |
| --- | --- |
| extractScene(fileName, password) | PDF 파일에서 3D 씬을 추출합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |
| 비밀번호 | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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



