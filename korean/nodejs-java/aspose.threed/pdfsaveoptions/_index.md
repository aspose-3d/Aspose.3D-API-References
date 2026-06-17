---
title: "PdfSaveOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

PDF 내보내기 시 저장 옵션.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | PdfSaveOptions의 생성자 |

 **Result:**



---


### getRenderMode{#getRenderMode}

| 이름 | 설명 |
| --- | --- |
| getRenderMode() | 렌더 모드는 3D 아트워크가 렌더링되는 스타일을 지정합니다. 속성 값은 PdfRenderMode 정수 상수입니다. |

 **Result:**



---


### setRenderMode{#setRenderMode}

| 이름 | 설명 |
| --- | --- |
| setRenderMode(value) | 렌더 모드는 3D 아트워크가 렌더링되는 스타일을 지정합니다. 속성 값은 PdfRenderMode 정수 상수입니다. |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| 이름 | 설명 |
| --- | --- |
| getLightingScheme() | LightingScheme은 3D 아트워크에 적용할 조명을 지정합니다. 속성 값은 PdfLightingScheme 정수 상수입니다. |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| 이름 | 설명 |
| --- | --- |
| setLightingScheme(value) | LightingScheme은 3D 아트워크에 적용할 조명을 지정합니다. 속성 값은 PdfLightingScheme 정수 상수입니다. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| 이름 | 설명 |
| --- | --- |
| getBackgroundColor() | PDF 파일의 3D 뷰 배경 색상. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| 이름 | 설명 |
| --- | --- |
| setBackgroundColor(value) | PDF 파일의 3D 뷰 배경 색상. |

 **Result:**



---


### getFaceColor{#getFaceColor}

| 이름 | 설명 |
| --- | --- |
| getFaceColor() | 3D 콘텐츠를 렌더링할 때 사용할 면 색상을 가져오거나 설정합니다. 이는 RenderMode가 Illustration 값일 때만 적용됩니다. |

 **Result:**



---


### setFaceColor{#setFaceColor}

| 이름 | 설명 |
| --- | --- |
| setFaceColor(value) | 3D 콘텐츠를 렌더링할 때 사용할 면 색상을 가져오거나 설정합니다. 이는 RenderMode가 Illustration 값일 때만 적용됩니다. |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| 이름 | 설명 |
| --- | --- |
| getAuxiliaryColor() | 3D 콘텐츠를 렌더링할 때 사용할 보조 색상을 가져오거나 설정합니다. 이 색상의 해석은 RenderMode에 따라 달라집니다. |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| 이름 | 설명 |
| --- | --- |
| setAuxiliaryColor(value) | 3D 콘텐츠를 렌더링할 때 사용할 보조 색상을 가져오거나 설정합니다. 이 색상의 해석은 RenderMode에 따라 달라집니다. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| 이름 | 설명 |
| --- | --- |
| getFlipCoordinateSystem() | 내보내는 동안 씬의 좌표계를 뒤집는지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| 이름 | 설명 |
| --- | --- |
| setFlipCoordinateSystem(value) | 내보내는 동안 씬의 좌표계를 뒤집는지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| 이름 | 설명 |
| --- | --- |
| getEmbedTextures() | 외부 텍스처를 PDF 파일에 삽입합니다. 기본값은 false입니다. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| 이름 | 설명 |
| --- | --- |
| setEmbedTextures(value) | 외부 텍스처를 PDF 파일에 삽입합니다. 기본값은 false입니다. |

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



