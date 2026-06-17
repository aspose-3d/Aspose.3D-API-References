---
title: "FbxSaveOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Fbx 파일 저장 옵션.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(format) | FbxSaveOptions를 초기화합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 형식 | 파일 형식 | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(contentType) | 최신 지원 버전을 사용하여 FbxSaveOptions를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| 이름 | 설명 |
| --- | --- |
| getReusePrimitiveMesh() | 같은 매개변수를 가진 프리미티브에 대해 메시를 재사용하면, 대량의 프리미티브 형태(예: CAD 파일에서 가져온)로 구성된 장면의 FBX 출력 크기를 크게 줄일 수 있습니다. 기본값은 false입니다. |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| 이름 | 설명 |
| --- | --- |
| setReusePrimitiveMesh(value) | 같은 매개변수를 가진 프리미티브에 대해 메시를 재사용하면, 대량의 프리미티브 형태(예: CAD 파일에서 가져온)로 구성된 장면의 FBX 출력 크기를 크게 줄일 수 있습니다. 기본값은 false입니다. |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| 이름 | 설명 |
| --- | --- |
| getEnableCompression() | FBX 파일에서 대용량 바이너리 데이터(예: 애니메이션 데이터, 제어점, 정점 요소 데이터, 인덱스)를 압축합니다. 기본값은 true입니다. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| 이름 | 설명 |
| --- | --- |
| setEnableCompression(value) | FBX 파일에서 대용량 바이너리 데이터(예: 애니메이션 데이터, 제어점, 정점 요소 데이터, 인덱스)를 압축합니다. 기본값은 true입니다. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| 이름 | 설명 |
| --- | --- |
| getFoldRepeatedCurveData() | 반복된 곡선 데이터를 재사용할지 여부를 가져오거나 설정합니다. 마지막 데이터의 참조 카운트를 증가시켜 재사용하면 true, 그렇지 않으면 false입니다. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| 이름 | 설명 |
| --- | --- |
| getExportLegacyMaterialProperties() | 레거시 재질 속성을 내보낼지 여부를 가져오거나 설정합니다. 이는 이전 호환성을 위해 사용됩니다. 이 옵션은 기본적으로 켜져 있습니다. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| 이름 | 설명 |
| --- | --- |
| setExportLegacyMaterialProperties(value) | 레거시 재질 속성을 내보낼지 여부를 가져오거나 설정합니다. 이는 이전 호환성을 위해 사용됩니다. 이 옵션은 기본적으로 켜져 있습니다. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| 이름 | 설명 |
| --- | --- |
| getVideoForTexture() | FBX로 내보낼 때 텍스처에 대한 Video 인스턴스를 생성할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| 이름 | 설명 |
| --- | --- |
| setVideoForTexture(value) | FBX로 내보낼 때 텍스처에 대한 Video 인스턴스를 생성할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| 이름 | 설명 |
| --- | --- |
| getEmbedTextures() | 텍스처를 최종 출력 파일에 포함시킬지 여부를 가져오거나 설정합니다. FBX Exporter는 파일 시스템에서 텍스처의 원시 데이터를 찾아 최종 FBX 파일에 포함시키려고 시도합니다. 기본값은 false입니다. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| 이름 | 설명 |
| --- | --- |
| setEmbedTextures(value) | 텍스처를 최종 출력 파일에 포함시킬지 여부를 가져오거나 설정합니다. FBX Exporter는 파일 시스템에서 텍스처의 원시 데이터를 찾아 최종 FBX 파일에 포함시키려고 시도합니다. 기본값은 false입니다. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| 이름 | 설명 |
| --- | --- |
| getGenerateVertexElementMaterial() | 첨부된 노드에 재질이 포함된 경우, 기하학에 항상 VertexElementMaterial을 생성할지 여부를 가져오거나 설정합니다. 기본적으로 이 옵션은 꺼져 있습니다. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| 이름 | 설명 |
| --- | --- |
| setGenerateVertexElementMaterial(value) | 첨부된 노드에 재질이 포함된 경우, 기하학에 항상 VertexElementMaterial을 생성할지 여부를 가져오거나 설정합니다. 기본적으로 이 옵션은 꺼져 있습니다. |

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



