---
title: "파일 형식"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

파일 형식 정의  @hideconstructor


## Properties

| 이름 | 설명 |
| --- | --- |
| MAYA_BINARY | 바이너리 형식의 Autodesk Maya |
| STL_BINARY | 바이너리 STL 파일 형식 |
| STLASCII | ASCII STL 파일 형식 |
| COLLADA | Collada 파일 형식 |
| GLTF | Khronos Group의 glTF |
| GLTF_BINARY | Khronos Group의 바이너리 형식 glTF |
| PDF | Adobe의 휴대용 문서 형식 |
| DXF | AutoCAD DXF |
| PLY | Polygon 파일 형식 또는 Stanford Triangle 형식 |
| X_BINARY | 바이너리 형식의 DirectX X 파일 |
| X_TEXT | 바이너리 형식의 DirectX X 파일 |
| DRACO | Google Draco 메시 |
| RVM_TEXT | AVEVA Plant Design Management System 모델을 텍스트 형식으로 |
| RVM_BINARY | AVEVA Plant Design Management System 모델을 바이너리 형식으로 |
| ASE | 3D Studio Max의 ASCII Scene Exporter 형식. |
| IFC | ISO 16739-1 Industry Foundation Classes 데이터 모델. |
| AMF | 적층 제조 파일 형식 |
| VRML | 가상 현실 모델링 언어 |
| ZIP | 다른 3D 파일 형식을 포함하는 Zip 아카이브. |
| USD | 범용 장면 설명 |
| USDZ | 압축된 범용 장면 설명 |
| XYZ | Xyz 포인트 클라우드 파일 |
| PCD | PCL 포인트 클라우드 데이터 파일을 ASCII 모드로 |
| PCD_BINARY | PCL 포인트 클라우드 데이터 파일을 바이너리 모드로 |

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


### getFormatByExtension{#getFormatByExtension}

| 이름 | 설명 |
| --- | --- |
| getFormatByExtension(extensionName) | 파일 확장자 이름에서 선호하는 파일 형식을 가져옵니다. 확장자 이름은 점('.')으로 시작해야 합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
파일 형식


---


### detect{#detect}

| 이름 | 설명 |
| --- | --- |
| detect(fileName) | 파일 이름으로 파일 형식을 감지합니다. 파일이 읽을 수 있어야 Aspose.3D가 파일 헤더를 통해 파일 형식을 감지할 수 있습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
파일 형식


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



