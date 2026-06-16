---
title: "UsdSaveOptions"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Simpan opsi untuk format USD/USDZ.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Inisialisasi UsdSaveOptions baru dengan format FileFormat.USD |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(fileFormat) | Inisialisasi UsdSaveOptions baru dengan format USD/USDZ yang ditentukan. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Nama | Deskripsi |
| --- | --- |
| getPrimitiveToMesh() | Mengonversi entitas primitif menjadi mesh selama ekspor. Atau langsung mengkodekan primitif ke file output (akan menggunakan definisi ekstensi Aspose untuk primitif tidak resmi seperti Dish, Torus). Nilai default adalah true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Nama | Deskripsi |
| --- | --- |
| setPrimitiveToMesh(value) | Mengonversi entitas primitif menjadi mesh selama ekspor. Atau langsung mengkodekan primitif ke file output (akan menggunakan definisi ekstensi Aspose untuk primitif tidak resmi seperti Dish, Torus). Nilai default adalah true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Nama | Deskripsi |
| --- | --- |
| getExportMetaData() | Mengekspor properti node melalui bidang customData milik USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Nama | Deskripsi |
| --- | --- |
| setExportMetaData(value) | Mengekspor properti node melalui bidang customData milik USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nama | Deskripsi |
| --- | --- |
| getMaterialConverter() | Konverter khusus untuk mengubah material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor USD akan secara otomatis mengubah material standar menjadi material PBR. Nilai default adalah null |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nama | Deskripsi |
| --- | --- |
| setMaterialConverter(value) | Konverter khusus untuk mengubah material geometri menjadi material PBR. Jika tidak ditetapkan, pengekspor USD akan secara otomatis mengubah material standar menjadi material PBR. Nilai default adalah null |

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



