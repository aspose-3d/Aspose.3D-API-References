---
title: "RvmSaveOptions"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Opsi penyimpanan untuk file RVM Avea PDMS.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Konstruktor RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(contentType) | Konstruktor RvmSaveOptions |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Nama | Deskripsi |
| --- | --- |
| getFileNote() | Catatan file di header file. |

 **Result:**



---


### setFileNote{#setFileNote}

| Nama | Deskripsi |
| --- | --- |
| setFileNote(value) | Catatan file di header file. |

 **Result:**



---


### getAuthor{#getAuthor}

| Nama | Deskripsi |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Nama | Deskripsi |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Nama | Deskripsi |
| --- | --- |
| getCreationTime() | Stempel waktu yang mengekspor file ini, nilai default adalah waktu saat ini |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Nama | Deskripsi |
| --- | --- |
| setCreationTime(value) | Stempel waktu yang mengekspor file ini, nilai default adalah waktu saat ini |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nama | Deskripsi |
| --- | --- |
| getAttributePrefix() | Mendapatkan atau mengatur awalan atribut yang akan diekspor, properti yang diekspor tidak akan mengandung awalan, properti khusus dengan awalan berbeda tidak akan diekspor, nilai default adalah 'rvm:'. Misalnya jika sebuah properti adalah rvm:Refno=345, atribut yang diekspor akan menjadi Refno = 345, awalan dihapus. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nama | Deskripsi |
| --- | --- |
| setAttributePrefix(value) | Mendapatkan atau mengatur awalan atribut yang akan diekspor, properti yang diekspor tidak akan mengandung awalan, properti khusus dengan awalan berbeda tidak akan diekspor, nilai default adalah 'rvm:'. Misalnya jika sebuah properti adalah rvm:Refno=345, atribut yang diekspor akan menjadi Refno = 345, awalan dihapus. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Nama | Deskripsi |
| --- | --- |
| getAttributeListFile() | Mendapatkan atau mengatur nama file daftar atribut, pengekspor akan menghasilkan nama berdasarkan nama file .rvm ketika properti ini tidak terdefinisi, nilai default adalah null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Nama | Deskripsi |
| --- | --- |
| setAttributeListFile(value) | Mendapatkan atau mengatur nama file daftar atribut, pengekspor akan menghasilkan nama berdasarkan nama file .rvm ketika properti ini tidak terdefinisi, nilai default adalah null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Nama | Deskripsi |
| --- | --- |
| getExportAttributes() | Mendapatkan atau mengatur apakah akan mengekspor daftar atribut ke file .att eksternal, nilai default adalah false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Nama | Deskripsi |
| --- | --- |
| setExportAttributes(value) | Mendapatkan atau mengatur apakah akan mengekspor daftar atribut ke file .att eksternal, nilai default adalah false. |

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



