---
title: "IOConfig"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

Konfigurasi IO untuk serialisasi/deserialisasi. Pengguna dapat menentukan konfigurasi terperinci seperti jalur pencarian dependensi atau konfigurasi terkait format di sini  @hideconstructor


## Metode

### getFileSystemFactory{#getFileSystemFactory}

| Nama | Deskripsi |
| --- | --- |
| getFileSystemFactory() | Mendapatkan atau mengatur kelas pabrik untuk FileSystem. Pabrik default akan membuat LocalFileSystem yang tidak cocok untuk lingkungan server. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Nama | Deskripsi |
| --- | --- |
| setFileSystemFactory(value) | Mendapatkan atau mengatur kelas pabrik untuk FileSystem. Pabrik default akan membuat LocalFileSystem yang tidak cocok untuk lingkungan server. |

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



