---
title: "RvmLoadOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

AVEVA Plant Design Management System의 RVM 파일에 대한 로드 옵션.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(contentType) | RvmLoadOptions 인스턴스를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | RvmLoadOptions 인스턴스를 생성합니다. |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| 이름 | 설명 |
| --- | --- |
| getGenerateMaterials() | RVM 파일에 색상 테이블이 내보내지지 않은 경우, 씬의 각 객체에 대해 무작위 색상으로 재료를 생성합니다. 기본값은 true입니다. |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| 이름 | 설명 |
| --- | --- |
| setGenerateMaterials(value) | RVM 파일에 색상 테이블이 내보내지지 않은 경우, 씬의 각 객체에 대해 무작위 색상으로 재료를 생성합니다. 기본값은 true입니다. |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| 이름 | 설명 |
| --- | --- |
| getCylinderRadialSegments() | 실린더의 방사형 세그먼트 수를 가져오거나 설정합니다. 기본값은 16입니다. |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| 이름 | 설명 |
| --- | --- |
| setCylinderRadialSegments(value) | 실린더의 방사형 세그먼트 수를 가져오거나 설정합니다. 기본값은 16입니다. |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| 이름 | 설명 |
| --- | --- |
| getDishLongitudeSegments() | 디시의 경도 세그먼트 수를 가져오거나 설정합니다. 기본값은 12입니다. |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| 이름 | 설명 |
| --- | --- |
| setDishLongitudeSegments(value) | 디시의 경도 세그먼트 수를 가져오거나 설정합니다. 기본값은 12입니다. |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| 이름 | 설명 |
| --- | --- |
| getDishLatitudeSegments() | 디시의 위도 세그먼트 수를 가져오거나 설정합니다. 기본값은 8입니다. |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| 이름 | 설명 |
| --- | --- |
| setDishLatitudeSegments(value) | 디시의 위도 세그먼트 수를 가져오거나 설정합니다. 기본값은 8입니다. |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| 이름 | 설명 |
| --- | --- |
| getTorusTubularSegments() | 토러스의 튜블러 세그먼트 수를 가져오거나 설정합니다. 기본값은 20입니다. |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| 이름 | 설명 |
| --- | --- |
| setTorusTubularSegments(value) | 토러스의 튜블러 세그먼트 수를 가져오거나 설정합니다. 기본값은 20입니다. |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| 이름 | 설명 |
| --- | --- |
| getRectangularTorusSegments() | 직사각형 토러스의 방사형 세그먼트 수를 가져오거나 설정합니다. 기본값은 20입니다. |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| 이름 | 설명 |
| --- | --- |
| setRectangularTorusSegments(value) | 직사각형 토러스의 방사형 세그먼트 수를 가져오거나 설정합니다. 기본값은 20입니다. |

 **Result:**



---


### getCenterScene{#getCenterScene}

| 이름 | 설명 |
| --- | --- |
| getCenterScene() | 로드된 후 장면을 중앙에 배치합니다. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| 이름 | 설명 |
| --- | --- |
| setCenterScene(value) | 로드된 후 장면을 중앙에 배치합니다. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| 이름 | 설명 |
| --- | --- |
| getAttributePrefix() | 외부 속성 파일에서 정의된 속성들의 접두사를 가져오거나 설정합니다. 접두사는 이름 충돌을 방지하기 위해 사용되며, 기본값은 "rvm:"입니다. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| 이름 | 설명 |
| --- | --- |
| setAttributePrefix(value) | 외부 속성 파일에서 정의된 속성들의 접두사를 가져오거나 설정합니다. 접두사는 이름 충돌을 방지하기 위해 사용되며, 기본값은 "rvm:"입니다. |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| 이름 | 설명 |
| --- | --- |
| getLookupAttributes() | 외부 속성 목록 파일(.att/.attrib/.txt)에서 속성을 로드할지 여부를 가져오거나 설정합니다. 기본값은 true입니다. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| 이름 | 설명 |
| --- | --- |
| setLookupAttributes(value) | 외부 속성 목록 파일(.att/.attrib/.txt)에서 속성을 로드할지 여부를 가져오거나 설정합니다. 기본값은 true입니다. |

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



