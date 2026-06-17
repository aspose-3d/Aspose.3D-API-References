---
title: "RvmSaveOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Aveva PDMS RVM 파일에 대한 저장 옵션.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | RvmSaveOptions의 생성자 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(contentType) | RvmSaveOptions의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| 이름 | 설명 |
| --- | --- |
| getFileNote() | 파일 헤더에 있는 파일 메모. |

 **Result:**



---


### setFileNote{#setFileNote}

| 이름 | 설명 |
| --- | --- |
| setFileNote(value) | 파일 헤더에 있는 파일 메모. |

 **Result:**



---


### getAuthor{#getAuthor}

| 이름 | 설명 |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| 이름 | 설명 |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| 이름 | 설명 |
| --- | --- |
| getCreationTime() | 이 파일을 내보낸 타임스탬프이며, 기본값은 현재 시간입니다. |

 **Result:**



---


### setCreationTime{#setCreationTime}

| 이름 | 설명 |
| --- | --- |
| setCreationTime(value) | 이 파일을 내보낸 타임스탬프이며, 기본값은 현재 시간입니다. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| 이름 | 설명 |
| --- | --- |
| getAttributePrefix() | 내보낼 속성의 접두사를 가져오거나 설정합니다. 내보낸 속성은 접두사가 없으며, 다른 접두사를 가진 사용자 정의 속성은 내보내지 않습니다. 기본값은 'rvm:'입니다. 예를 들어 속성이 rvm:Refno=345인 경우, 내보낸 속성은 Refno = 345가 되며, 접두사가 제거됩니다. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| 이름 | 설명 |
| --- | --- |
| setAttributePrefix(value) | 내보낼 속성의 접두사를 가져오거나 설정합니다. 내보낸 속성은 접두사가 없으며, 다른 접두사를 가진 사용자 정의 속성은 내보내지 않습니다. 기본값은 'rvm:'입니다. 예를 들어 속성이 rvm:Refno=345인 경우, 내보낸 속성은 Refno = 345가 되며, 접두사가 제거됩니다. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| 이름 | 설명 |
| --- | --- |
| getAttributeListFile() | 속성 목록 파일의 파일 이름을 가져오거나 설정합니다. 이 속성이 정의되지 않은 경우 내보내기 프로그램은 .rvm 파일 이름을 기반으로 이름을 생성합니다. 기본값은 null입니다. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| 이름 | 설명 |
| --- | --- |
| setAttributeListFile(value) | 속성 목록 파일의 파일 이름을 가져오거나 설정합니다. 이 속성이 정의되지 않은 경우 내보내기 프로그램은 .rvm 파일 이름을 기반으로 이름을 생성합니다. 기본값은 null입니다. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| 이름 | 설명 |
| --- | --- |
| getExportAttributes() | 속성 목록을 외부 .att 파일로 내보낼지 여부를 가져오거나 설정합니다. 기본값은 false입니다. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| 이름 | 설명 |
| --- | --- |
| setExportAttributes(value) | 속성 목록을 외부 .att 파일로 내보낼지 여부를 가져오거나 설정합니다. 기본값은 false입니다. |

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



