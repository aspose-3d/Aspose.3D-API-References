---
title: "IOConfig"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

직렬화/역직렬화를 위한 IO 구성. 사용자는 종속성 조회 경로와 같은 상세 구성을 지정하거나 여기에서 형식 관련 구성을 지정할 수 있습니다.  @hideconstructor


## 메서드

### getFileSystemFactory{#getFileSystemFactory}

| 이름 | 설명 |
| --- | --- |
| getFileSystemFactory() | FileSystem에 대한 팩터리 클래스를 가져오거나 설정합니다. 기본 팩터리는 LocalFileSystem을 생성하지만 서버 환경에는 적합하지 않습니다. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| 이름 | 설명 |
| --- | --- |
| setFileSystemFactory(value) | FileSystem에 대한 팩터리 클래스를 가져오거나 설정합니다. 기본 팩터리는 LocalFileSystem을 생성하지만 서버 환경에는 적합하지 않습니다. |

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



