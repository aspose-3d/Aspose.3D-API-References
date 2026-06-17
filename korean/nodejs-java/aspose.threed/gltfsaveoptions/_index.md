---
title: "GltfSaveOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

glTF 형식에 대한 저장 옵션.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(contentType) | GltfSaveOptions의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(format) | GltfSaveOptions의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 형식 | 파일 형식 | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| 이름 | 설명 |
| --- | --- |
| getPrettyPrint() | GLTF 파일의 JSON 내용은 사람이 읽기 쉽도록 들여쓰기 되며, 기본값은 false입니다. |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| 이름 | 설명 |
| --- | --- |
| setPrettyPrint(value) | GLTF 파일의 JSON 내용은 사람이 읽기 쉽도록 들여쓰기 되며, 기본값은 false입니다. |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| 이름 | 설명 |
| --- | --- |
| getFallbackNormal() | GLTF2 내보내기에서 잘못된 노멀을 감지하면, 검증을 우회하기 위해 원래 값 대신 이 값이 사용됩니다. 기본값은 (0, 1, 0)입니다. |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| 이름 | 설명 |
| --- | --- |
| getEmbedAssets() | 외부 자산을 모두 base64로 인코딩하여 ASCII 모드의 단일 파일에 포함합니다. 기본값은 false입니다. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| 이름 | 설명 |
| --- | --- |
| setEmbedAssets(value) | 외부 자산을 모두 base64로 인코딩하여 ASCII 모드의 단일 파일에 포함합니다. 기본값은 false입니다. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| 이름 | 설명 |
| --- | --- |
| getImageFormat() | 표준 glTF는 텍스처 형식으로 PNG/JPG만 지원하며, 이 옵션은 내보내기 중 Aspose.3D가 비표준 이미지를 지원되는 형식으로 변환하는 방법을 안내합니다. 기본값은 GltfEmbeddedImageFormat.PNG이며, 해당 속성의 값은 GltfEmbeddedImageFormat 정수 상수입니다. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| 이름 | 설명 |
| --- | --- |
| setImageFormat(value) | 표준 glTF는 텍스처 형식으로 PNG/JPG만 지원하며, 이 옵션은 내보내기 중 Aspose.3D가 비표준 이미지를 지원되는 형식으로 변환하는 방법을 안내합니다. 기본값은 GltfEmbeddedImageFormat.PNG이며, 해당 속성의 값은 GltfEmbeddedImageFormat 정수 상수입니다. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| 이름 | 설명 |
| --- | --- |
| getMaterialConverter() | 지오메트리의 재질을 PBR 재질로 변환하는 사용자 지정 컨버터입니다. 이 값이 지정되지 않은 경우 glTF 2.0 내보내기는 표준 재질을 자동으로 PBR 재질로 변환합니다. 기본값은 null이며, 이 속성은 씬을 glTF 2.0 파일로 내보낼 때 사용됩니다. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| 이름 | 설명 |
| --- | --- |
| setMaterialConverter(value) | 지오메트리의 재질을 PBR 재질로 변환하는 사용자 지정 컨버터입니다. 이 값이 지정되지 않은 경우 glTF 2.0 내보내기는 표준 재질을 자동으로 PBR 재질로 변환합니다. 기본값은 null이며, 이 속성은 씬을 glTF 2.0 파일로 내보낼 때 사용됩니다. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| 이름 | 설명 |
| --- | --- |
| getUseCommonMaterials() | KHR 공통 재질 확장을 사용하여 재질을 직렬화합니다. 기본값은 false입니다. 이를 false로 설정하면 Aspose.3D가 vertex/fragment 셰이더 집합을 내보내게 됩니다 #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| 이름 | 설명 |
| --- | --- |
| setUseCommonMaterials(value) | KHR 공통 재질 확장을 사용하여 재질을 직렬화합니다. 기본값은 false입니다. 이를 false로 설정하면 Aspose.3D가 vertex/fragment 셰이더 집합을 내보내게 됩니다 #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| 이름 | 설명 |
| --- | --- |
| getExternalDracoEncoder() | 외부 draco 인코더를 사용하여 draco 압축 속도를 가속화합니다. Aspose.3D는 메시를 draco 형식으로 인코딩하기 위해 새로운 하위 프로세스를 생성하며, 사용은 사용자 책임 하에 진행됩니다. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| 이름 | 설명 |
| --- | --- |
| setExternalDracoEncoder(value) | 외부 draco 인코더를 사용하여 draco 압축 속도를 가속화합니다. Aspose.3D는 메시를 draco 형식으로 인코딩하기 위해 새로운 하위 프로세스를 생성하며, 사용은 사용자 책임 하에 진행됩니다. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| 이름 | 설명 |
| --- | --- |
| getFlipTexCoordV() | 텍스처 좌표 v(t) 구성 요소를 뒤집습니다. 기본값은 true입니다. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| 이름 | 설명 |
| --- | --- |
| setFlipTexCoordV(value) | 텍스처 좌표 v(t) 구성 요소를 뒤집습니다. 기본값은 true입니다. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| 이름 | 설명 |
| --- | --- |
| getBufferFile() | 바이너리 데이터를 저장하는 외부 버퍼 파일의 파일 이름입니다. 이 파일이 지정되지 않으면 Aspose.3D가 이름을 자동으로 생성합니다. 이 설정은 바이너리 모드로 glTF를 내보낼 때 무시됩니다. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| 이름 | 설명 |
| --- | --- |
| setBufferFile(value) | 바이너리 데이터를 저장하는 외부 버퍼 파일의 파일 이름입니다. 이 파일이 지정되지 않으면 Aspose.3D가 이름을 자동으로 생성합니다. 이 설정은 바이너리 모드로 glTF를 내보낼 때 무시됩니다. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| 이름 | 설명 |
| --- | --- |
| getSaveExtras() | 생성된 glTF 파일의 'extra' 필드에 씬 객체의 동적 속성을 저장합니다. 이는 애플리케이션별 데이터를 제공하는 데 유용합니다. 기본값은 false입니다. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| 이름 | 설명 |
| --- | --- |
| setSaveExtras(value) | 생성된 glTF 파일의 'extra' 필드에 씬 객체의 동적 속성을 저장합니다. 이는 애플리케이션별 데이터를 제공하는 데 유용합니다. 기본값은 false입니다. |

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


### getDracoCompression{#getDracoCompression}

| 이름 | 설명 |
| --- | --- |
| getDracoCompression() | draco 압축을 활성화할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| 이름 | 설명 |
| --- | --- |
| setDracoCompression(value) | draco 압축을 활성화할지 여부를 가져오거나 설정합니다. |

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



