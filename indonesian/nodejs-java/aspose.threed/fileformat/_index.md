---
title: "FileFormat"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Definisi format file  @hideconstructor


## Properti

| Nama | Deskripsi |
| --- | --- |
| MAYA_BINARY | Autodesk Maya dalam format biner |
| STL_BINARY | Format file STL biner |
| STLASCII | Format file STL ASCII |
| COLLADA | Format file Collada |
| GLTF | glTF milik Khronos Group |
| GLTF_BINARY | glTF milik Khronos Group dalam format biner |
| PDF | Format Dokumen Portabel Adobe |
| DXF | AutoCAD DXF |
| PLY | Format File Polygon atau Format Segitiga Stanford |
| X_BINARY | File X DirectX dalam format biner |
| X_TEXT | File X DirectX dalam format biner |
| DRACO | Mesh Draco Google |
| RVM_TEXT | Model AVEVA Plant Design Management System dalam format teks |
| RVM_BINARY | Model AVEVA Plant Design Management System dalam format biner |
| ASE | Format ASCII Scene Exporter 3D Studio Max. |
| IFC | Model data ISO 16739-1 Industry Foundation Classes. |
| AMF | Format berkas manufaktur aditif |
| VRML | Bahasa Pemodelan Realitas Virtual |
| ZIP | Arsip Zip yang berisi format berkas 3d lainnya. |
| USD | Deskripsi Adegan Universal |
| USDZ | Deskripsi Adegan Universal Terkompresi |
| XYZ | Berkas awan titik Xyz |
| PCD | Berkas PCL Point Cloud Data dalam mode ASCII |
| PCD_BINARY | Berkas PCL Point Cloud Data dalam mode Biner |

## Metode

### getVersion{#getVersion}

| Nama | Deskripsi |
| --- | --- |
| getVersion() | Mendapatkan versi format file |

 **Result:**



---


### getExtension{#getExtension}

| Nama | Deskripsi |
| --- | --- |
| getExtension() | Mendapatkan nama ekstensi dari tipe ini. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nama | Deskripsi |
| --- | --- |
| getExtensions() | Mendapatkan nama-nama ekstensi dari tipe ini. |

 **Result:**



---


### getContentType{#getContentType}

| Nama | Deskripsi |
| --- | --- |
| getContentType() | Mendapatkan tipe konten format file Nilai properti adalah konstanta integer FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nama | Deskripsi |
| --- | --- |
| getFileFormatType() | Mendapatkan tipe format file |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| Nama | Deskripsi |
| --- | --- |
| getFormatByExtension(extensionName) | Mendapatkan format file yang disukai dari nama ekstensi file Nama ekstensi harus dimulai dengan titik ('.'). |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


---


### detect{#detect}

| Nama | Deskripsi |
| --- | --- |
| detect(fileName) | Deteksi format file dari nama file, file harus dapat dibaca sehingga Aspose.3D dapat mendeteksi format file melalui header file. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


---


### createLoadOptions{#createLoadOptions}

| Nama | Deskripsi |
| --- | --- |
| createLoadOptions() | Buat opsi muat default untuk format file ini |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nama | Deskripsi |
| --- | --- |
| createSaveOptions() | Buat opsi simpan default untuk format file ini |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Format menjadi string |

 **Result:**
String


---



