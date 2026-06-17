---
title: "DracoSaveOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/dracosaveoptions/
---
## DracoSaveOptions class

Google Draco 파일 저장 옵션


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | draco 파일을 저장하기 위한 기본 구성을 생성합니다. |

 **Result:**



---


### getPositionBits{#getPositionBits}

| 이름 | 설명 |
| --- | --- |
| getPositionBits() | 위치에 대한 양자화 비트, 기본값은 14입니다. |

 **Result:**



---


### setPositionBits{#setPositionBits}

| 이름 | 설명 |
| --- | --- |
| setPositionBits(value) | 위치에 대한 양자화 비트, 기본값은 14입니다. |

 **Result:**



---


### getTextureCoordinateBits{#getTextureCoordinateBits}

| 이름 | 설명 |
| --- | --- |
| getTextureCoordinateBits() | 텍스처 좌표에 대한 양자화 비트, 기본값은 12입니다. |

 **Result:**



---


### setTextureCoordinateBits{#setTextureCoordinateBits}

| 이름 | 설명 |
| --- | --- |
| setTextureCoordinateBits(value) | 텍스처 좌표에 대한 양자화 비트, 기본값은 12입니다. |

 **Result:**



---


### getColorBits{#getColorBits}

| 이름 | 설명 |
| --- | --- |
| getColorBits() | 버텍스 색상에 대한 양자화 비트, 기본값은 10입니다. |

 **Result:**



---


### setColorBits{#setColorBits}

| 이름 | 설명 |
| --- | --- |
| setColorBits(value) | 버텍스 색상에 대한 양자화 비트, 기본값은 10입니다. |

 **Result:**



---


### getNormalBits{#getNormalBits}

| 이름 | 설명 |
| --- | --- |
| getNormalBits() | 노멀 벡터에 대한 양자화 비트, 기본값은 10입니다. |

 **Result:**



---


### setNormalBits{#setNormalBits}

| 이름 | 설명 |
| --- | --- |
| setNormalBits(value) | 노멀 벡터에 대한 양자화 비트, 기본값은 10입니다. |

 **Result:**



---


### getCompressionLevel{#getCompressionLevel}

| 이름 | 설명 |
| --- | --- |
| getCompressionLevel() | 압축 수준, 기본값은 DracoCompressionLevel.STANDARD입니다. 속성 값은 DracoCompressionLevel 정수 상수입니다. |

 **Result:**



---


### setCompressionLevel{#setCompressionLevel}

| 이름 | 설명 |
| --- | --- |
| setCompressionLevel(value) | 압축 수준, 기본값은 DracoCompressionLevel.STANDARD입니다. 속성 값은 DracoCompressionLevel 정수 상수입니다. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| 이름 | 설명 |
| --- | --- |
| getApplyUnitScale() | AssetInfo.UnitScaleFactor를 메시에 적용합니다. 기본값은 false입니다. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| 이름 | 설명 |
| --- | --- |
| setApplyUnitScale(value) | AssetInfo.UnitScaleFactor를 메시에 적용합니다. 기본값은 false입니다. |

 **Result:**



---


### getPointCloud{#getPointCloud}

| 이름 | 설명 |
| --- | --- |
| getPointCloud() | 장면을 포인트 클라우드로 내보내며, 기본값은 false입니다. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| 이름 | 설명 |
| --- | --- |
| setPointCloud(value) | 장면을 포인트 클라우드로 내보내며, 기본값은 false입니다. |

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



