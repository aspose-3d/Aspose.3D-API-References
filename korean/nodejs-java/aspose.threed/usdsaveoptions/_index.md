---
title: "UsdSaveOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

USD/USDZ 형식에 대한 저장 옵션.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | FileFormat.USD 형식으로 새로운 UsdSaveOptions를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(fileFormat) | 지정된 USD/USDZ 형식으로 새로운 UsdSaveOptions를 초기화합니다. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| 이름 | 설명 |
| --- | --- |
| getPrimitiveToMesh() | 내보내기 중에 기본 엔터티를 메쉬로 변환합니다. 또는 기본 엔터티를 출력 파일에 직접 인코딩합니다(비공식 기본 엔터티인 Dish, Torus 등에 대해 Aspose의 확장 정의를 사용합니다). 기본값은 true입니다. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| 이름 | 설명 |
| --- | --- |
| setPrimitiveToMesh(value) | 내보내기 중에 기본 엔터티를 메쉬로 변환합니다. 또는 기본 엔터티를 출력 파일에 직접 인코딩합니다(비공식 기본 엔터티인 Dish, Torus 등에 대해 Aspose의 확장 정의를 사용합니다). 기본값은 true입니다. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| 이름 | 설명 |
| --- | --- |
| getExportMetaData() | USD의 customData 필드를 통해 노드의 속성을 내보냅니다. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| 이름 | 설명 |
| --- | --- |
| setExportMetaData(value) | USD의 customData 필드를 통해 노드의 속성을 내보냅니다. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| 이름 | 설명 |
| --- | --- |
| getMaterialConverter() | 기하학 재질을 PBR 재질로 변환하는 사용자 지정 변환기입니다. 이 값이 지정되지 않은 경우 USD 내보내기 프로그램은 표준 재질을 자동으로 PBR 재질로 변환합니다. 기본값은 null입니다. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| 이름 | 설명 |
| --- | --- |
| setMaterialConverter(value) | 기하학 재질을 PBR 재질로 변환하는 사용자 지정 변환기입니다. 이 값이 지정되지 않은 경우 USD 내보내기 프로그램은 표준 재질을 자동으로 PBR 재질로 변환합니다. 기본값은 null입니다. |

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



