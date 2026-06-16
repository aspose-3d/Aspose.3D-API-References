---
title: "MemoryFileSystem"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem 将把读写操作映射到内存。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| 名称 | 描述 |
| --- | --- |
| getFileNames() | 此内存文件系统中的文件名。 |

 **Result:**



---


### getFileContent{#getFileContent}

| 名称 | 描述 |
| --- | --- |
| getFileContent(fileName) | 返回指定文件的原始内容。如果指定的文件不存在，则抛出 System.IO.FileNotFoundException。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| 名称 | 描述 |
| --- | --- |
| readFile(fileName, options) | 创建用于读取依赖项的流。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |
| 选项 | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| 名称 | 描述 |
| --- | --- |
| writeFile(fileName, options) | 创建用于写入依赖项的流。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |
| 选项 | IOConfig | null |

 **Result:**
Stream


---



