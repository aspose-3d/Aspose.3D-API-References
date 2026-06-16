---
title: "ZipArchiveFileSystem"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

文件系统用于提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(fileName) | 通过文件名构造 ZipArchiveFileSystem。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |

 **Result:**



---


### readFile{#readFile}

| 名称 | 描述 |
| --- | --- |
| readFile(fileName, options) | 打开文件进行读取 |

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
| writeFile(fileName, options) | 打开文件进行写入，此类未实现。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |
| 选项 | IOConfig | null |

 **Result:**
Stream


---



