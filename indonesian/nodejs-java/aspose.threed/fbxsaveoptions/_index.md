---
title: "FbxSaveOptions"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Opsi penyimpanan untuk file Fbx.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(format) | Menginisialisasi sebuah FbxSaveOptions |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| bentuk | FileFormat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(contentType) | Inisialisasi sebuah FbxSaveOptions menggunakan versi terbaru yang didukung. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Nama | Deskripsi |
| --- | --- |
| getReusePrimitiveMesh() | Gunakan kembali mesh untuk primitif dengan parameter yang sama, ini akan secara signifikan mengurangi ukuran output FBX yang dibangun dari sekumpulan besar bentuk primitif (seperti yang diimpor dari file CAD). Nilai default adalah false |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Nama | Deskripsi |
| --- | --- |
| setReusePrimitiveMesh(value) | Gunakan kembali mesh untuk primitif dengan parameter yang sama, ini akan secara signifikan mengurangi ukuran output FBX yang dibangun dari sekumpulan besar bentuk primitif (seperti yang diimpor dari file CAD). Nilai default adalah false |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Nama | Deskripsi |
| --- | --- |
| getEnableCompression() | Kompresi data biner besar dalam file FBX (misalnya data animasi, titik kontrol, data elemen vertex, indeks), nilai default adalah true. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Nama | Deskripsi |
| --- | --- |
| setEnableCompression(value) | Kompresi data biner besar dalam file FBX (misalnya data animasi, titik kontrol, data elemen vertex, indeks), nilai default adalah true. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Nama | Deskripsi |
| --- | --- |
| getFoldRepeatedCurveData() | Mendapatkan atau mengatur apakah menggunakan kembali data kurva berulang dengan meningkatkan hitungan referensi data terakhir, true jika data kurva berulang dilipat; jika tidak, false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Nama | Deskripsi |
| --- | --- |
| getExportLegacyMaterialProperties() | Mendapatkan atau mengatur apakah mengekspor properti material warisan, digunakan untuk kompatibilitas mundur. Opsi ini diaktifkan secara default. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Nama | Deskripsi |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Mendapatkan atau mengatur apakah mengekspor properti material warisan, digunakan untuk kompatibilitas mundur. Opsi ini diaktifkan secara default. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Nama | Deskripsi |
| --- | --- |
| getVideoForTexture() | Mendapatkan atau mengatur apakah menghasilkan instance Video untuk Tekstur saat mengekspor sebagai FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Nama | Deskripsi |
| --- | --- |
| setVideoForTexture(value) | Mendapatkan atau mengatur apakah menghasilkan instance Video untuk Tekstur saat mengekspor sebagai FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Nama | Deskripsi |
| --- | --- |
| getEmbedTextures() | Mendapatkan atau mengatur apakah menyematkan tekstur ke file output akhir. FBX Exporter akan mencoba menemukan data mentah tekstur dari FileSystem, dan menyematkan file ke file FBX akhir. Nilai default adalah false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Nama | Deskripsi |
| --- | --- |
| setEmbedTextures(value) | Mendapatkan atau mengatur apakah menyematkan tekstur ke file output akhir. FBX Exporter akan mencoba menemukan data mentah tekstur dari FileSystem, dan menyematkan file ke file FBX akhir. Nilai default adalah false. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Nama | Deskripsi |
| --- | --- |
| getGenerateVertexElementMaterial() | Mendapatkan atau mengatur apakah selalu menghasilkan VertexElementMaterial untuk geometri jika node yang terlampir berisi material. Ini dimatikan secara default. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Nama | Deskripsi |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Mendapatkan atau mengatur apakah selalu menghasilkan VertexElementMaterial untuk geometri jika node yang terlampir berisi material. Ini dimatikan secara default. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nama | Deskripsi |
| --- | --- |
| getExportTextures() | Coba salin tekstur yang digunakan dalam adegan ke direktori output. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nama | Deskripsi |
| --- | --- |
| setExportTextures(value) | Coba salin tekstur yang digunakan dalam adegan ke direktori output. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nama | Deskripsi |
| --- | --- |
| getFileFormat() | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nama | Deskripsi |
| --- | --- |
| getEncoding() | Mendapatkan atau mengatur enkoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan memutuskan enkoding mana yang akan digunakan. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nama | Deskripsi |
| --- | --- |
| getFileSystem() | Izinkan pengguna mengelola cara menangani ketergantungan eksternal selama memuat/menyimpan. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nama | Deskripsi |
| --- | --- |
| setFileSystem(value) | Izinkan pengguna mengelola cara menangani ketergantungan eksternal selama memuat/menyimpan. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nama | Deskripsi |
| --- | --- |
| getLookupPaths() | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |

 **Result:**



---


### getFileName{#getFileName}

| Nama | Deskripsi |
| --- | --- |
| getFileName() | Nama file dari adegan yang diekspor/dimpor. Ini bersifat opsional, tetapi berguna saat menyerialisasi aset eksternal seperti material OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nama | Deskripsi |
| --- | --- |
| setFileName(value) | Nama file dari adegan yang diekspor/dimpor. Ini bersifat opsional, tetapi berguna saat menyerialisasi aset eksternal seperti material OBJ. |

 **Result:**



---



