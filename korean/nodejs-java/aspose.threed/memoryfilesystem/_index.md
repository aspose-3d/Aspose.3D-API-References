---
title: "MemoryFileSystem"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem 은 읽기/쓰기 작업을 메모리로 매핑합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| 이름 | 설명 |
| --- | --- |
| getFileNames() | 이 메모리 파일 시스템에 있는 파일 이름들. |

 **Result:**



---


### getFileContent{#getFileContent}

| 이름 | 설명 |
| --- | --- |
| getFileContent(fileName) | 지정된 파일의 원시 콘텐츠를 반환합니다. 지정된 파일이 존재하지 않을 경우 System.IO.FileNotFoundException을 발생시킵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| 이름 | 설명 |
| --- | --- |
| readFile(fileName, options) | 종속성을 읽기 위한 스트림을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |
| 옵션 | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| 이름 | 설명 |
| --- | --- |
| writeFile(fileName, options) | 종속성을 쓰기 위한 스트림을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileNam | String | null |
| 옵션 | IOConfig | null |

 **Result:**
Stream


---



