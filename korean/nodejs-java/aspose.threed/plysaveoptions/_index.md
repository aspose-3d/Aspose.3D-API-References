---
title: "PlySaveOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

씬을 PLY 파일로 내보내기 위한 저장 옵션.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | PlySaveOptions의 생성자 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(contentType) | PlySaveOptions의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| 이름 | 설명 |
| --- | --- |
| getPointCloud() | 씬을 포인트 클라우드로 내보냅니다. 기본값은 false입니다. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| 이름 | 설명 |
| --- | --- |
| setPointCloud(value) | 씬을 포인트 클라우드로 내보냅니다. 기본값은 false입니다. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| 이름 | 설명 |
| --- | --- |
| getFlipCoordinate() | 씬을 저장하는 동안 좌표를 뒤집습니다. 기본값은 true입니다. |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| 이름 | 설명 |
| --- | --- |
| setFlipCoordinate(value) | 씬을 저장하는 동안 좌표를 뒤집습니다. 기본값은 true입니다. |

 **Result:**



---


### getVertexElement{#getVertexElement}

| 이름 | 설명 |
| --- | --- |
| getVertexElement() | 정점 데이터의 요소 이름이며, 기본값은 "vertex"입니다. |

 **Result:**



---


### setVertexElement{#setVertexElement}

| 이름 | 설명 |
| --- | --- |
| setVertexElement(value) | 정점 데이터의 요소 이름이며, 기본값은 "vertex"입니다. |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| 이름 | 설명 |
| --- | --- |
| getPositionComponents() | 위치 데이터의 구성 요소 이름이며, 기본값은 ("x", "y", "z")입니다. |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| 이름 | 설명 |
| --- | --- |
| getNormalComponents() | 노멀 데이터의 구성 요소 이름이며, 기본값은 ("nx", "ny", "nz")입니다. |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| 이름 | 설명 |
| --- | --- |
| getTextureCoordinateComponents() | 텍스처 좌표 데이터의 구성 요소 이름이며, 기본값은 ("u", "v")입니다. |

 **Result:**



---


### getColorComponents{#getColorComponents}

| 이름 | 설명 |
| --- | --- |
| getColorComponents() | 버텍스 색상의 구성 요소 이름이며, 기본값은 ("red", "green", "blue")입니다. |

 **Result:**



---


### getFaceElement{#getFaceElement}

| 이름 | 설명 |
| --- | --- |
| getFaceElement() | 페이스 데이터의 요소 이름이며, 기본값은 "face"입니다. |

 **Result:**



---


### setFaceElement{#setFaceElement}

| 이름 | 설명 |
| --- | --- |
| setFaceElement(value) | 페이스 데이터의 요소 이름이며, 기본값은 "face"입니다. |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| 이름 | 설명 |
| --- | --- |
| getFaceProperty() | 페이스 데이터의 속성 이름이며, 기본값은 "vertex_index"입니다. |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| 이름 | 설명 |
| --- | --- |
| setFaceProperty(value) | 페이스 데이터의 속성 이름이며, 기본값은 "vertex_index"입니다. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| 이름 | 설명 |
| --- | --- |
| getExportTextures() | 씬에서 사용된 텍스처를 출력 디렉터리로 복사합니다. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| 이름 | 설명 |
| --- | --- |
| setExportTextures(value) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사합니다. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| 이름 | 설명 |
| --- | --- |
| getFileFormat() | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |

 **Result:**



---


### getEncoding{#getEncoding}

| 이름 | 설명 |
| --- | --- |
| getEncoding() | 텍스트 기반 파일에 대한 기본 인코딩을 가져오거나 설정합니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| 이름 | 설명 |
| --- | --- |
| getFileSystem() | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| 이름 | 설명 |
| --- | --- |
| setFileSystem(value) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| 이름 | 설명 |
| --- | --- |
| getLookupPaths() | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 조회 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 합니다. |

 **Result:**



---


### getFileName{#getFileName}

| 이름 | 설명 |
| --- | --- |
| getFileName() | 내보내기/가져오기 씬의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다. |

 **Result:**



---


### setFileName{#setFileName}

| 이름 | 설명 |
| --- | --- |
| setFileName(value) | 내보내기/가져오기 씬의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다. |

 **Result:**



---



