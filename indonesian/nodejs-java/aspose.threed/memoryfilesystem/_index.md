---
title: "MemoryFileSystem"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem akan memetakan operasi baca/tulis ke memori.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Nama | Deskripsi |
| --- | --- |
| getFileNames() | Nama file yang ada dalam sistem file memori ini. |

 **Result:**



---


### getFileContent{#getFileContent}

| Nama | Deskripsi |
| --- | --- |
| getFileContent(fileName) | Mengembalikan konten mentah dari file yang ditentukan. Melempar System.IO.FileNotFoundException jika file yang ditentukan tidak ada. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Nama | Deskripsi |
| --- | --- |
| readFile(fileName, options) | Buat sebuah stream untuk membaca dependensi. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Nama | Deskripsi |
| --- | --- |
| writeFile(fileName, options) | Buat sebuah stream untuk menulis dependensi. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---



